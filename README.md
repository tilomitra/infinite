# Infinite CSS Animations
A small set of useful infinite CSS animations that you can drop into your project.

[View Docs and Demo](http://tilomitra.github.io/infinite)

## Usage
### pulsate
```
@-webkit-keyframes pulsate {
     0% {-webkit-transform: scale(0.1, 0.1); opacity: 0.0;}
     50% {opacity: 1.0;}
     100% {-webkit-transform: scale(1.2, 1.2); opacity: 0.0;}
 }

.pulsate-css {
    animation: pulsate 1s ease-out;
    animation-iteration-count: infinite;
    opacity: 0.0;
}
```

## opacityPulsate
```
@-webkit-keyframes opacityPulse {
0% {opacity: 0.0;}
50% {opacity: 1.0;}
100% {opacity: 0.0;}
}

.opacityPulse-css {
    animation: opacityPulse 2s ease-out;
    animation-iteration-count: infinite;
    opacity: 1;
}
```

## alertPulse
```
@-webkit-keyframes alertPulse {
    0% {background-color: #9A2727; opacity: 1;}
    50% {opacity: red; opacity: 0.75; }
    100% {opacity: #9A2727; opacity: 1;}
}

.alertPulse-css {
    animation: alertPulse 2s ease-out;
    animation-iteration-count: infinite;
    opacity: 1;
    background: #9A2727; /* you need this to specify a color to pulse to */
}
```

## rotating
```
@keyframes rotating {
  from {
    -ms-transform: rotate(0deg);
    -moz-transform: rotate(0deg);
    -webkit-transform: rotate(0deg);
    -o-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  to {
    -ms-transform: rotate(360deg);
    -moz-transform: rotate(360deg);
    -webkit-transform: rotate(360deg);
    -o-transform: rotate(360deg);
    transform: rotate(360deg);
  }
}

.rotating-css {
    animation: rotating 2s linear;
    animation-iteration-count: infinite;
}
```

## License
MIT License.