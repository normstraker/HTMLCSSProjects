# Animation Property Project

- Responsive mock-up hero page

## CSS

- z-index:
- position: sticky;
- text-transform: uppercase; text-transform: capitalize;
- width: 90vw;
  max-width: 1170px;
  margin: 0 auto;
- @media screen and (min-width: 768px)
- min-height: calc(100vh - 5rem);
- position: relative;
- background: linear-gradient(to right, rgba(182, 180, 180, 0.1),rgb(80, 41, 4)), url("./hero-bcg.jpg") center/cover;
- position: absolute;
  top: 50%;
  left: 50%;
- transform: translate(-50%, -50%);
- text-align: center;
- animation: slideFromBottom 5s ease-in-out 1;
- animation: slideFromTop 5s ease-in-out 1;
- @keyframes slideFromTop {
  0% {
  opacity: 0;
  transform: translateY(-100px);
  }
  100% {
  opacity: 1;
  transform: translateY(0);
  }
  }
- @keyframes slideFromBottom {
  0% {
  opacity: 0;
  transform: translateY(100px);
  }
  100% {
  opacity: 1;
  transform: translateY(0);
  }
  }
