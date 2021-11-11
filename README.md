# Jennifer Adams
Fall 2021- Web Design Principles MMC5277

## Resources
I used the setup of the Hover Hang effect found on the following website, which was mentioned in one of your videos:

[Click Here to View](https://ianlunn.github.io/Hover/ 
)

I used this to create a piece of the blood droplet effect; the portion where it is stationary and bouncing up and down. I had to modify the code in order to make it work the way I intended. 

The original code is below:

``` css
@-webkit-keyframes hvr-hang {
  0% {
    -webkit-transform: translateY(8px);
    transform: translateY(8px);
  }
  50% {
    -webkit-transform: translateY(4px);
    transform: translateY(4px);
  }
  100% {
    -webkit-transform: translateY(8px);
    transform: translateY(8px);
  }
}
@keyframes hvr-hang {
  0% {
    -webkit-transform: translateY(8px);
    transform: translateY(8px);
  }
  50% {
    -webkit-transform: translateY(4px);
    transform: translateY(4px);
  }
  100% {
    -webkit-transform: translateY(8px);
    transform: translateY(8px);
  }
}
@-webkit-keyframes hvr-hang-sink {
  100% {
    -webkit-transform: translateY(8px);
    transform: translateY(8px);
  }
}
@keyframes hvr-hang-sink {
  100% {
    -webkit-transform: translateY(8px);
    transform: translateY(8px);
  }
}
.hvr-hang {
  display: inline-block;
  vertical-align: middle;
  -webkit-transform: perspective(1px) translateZ(0);
  transform: perspective(1px) translateZ(0);
  box-shadow: 0 0 1px rgba(0, 0, 0, 0);
}
.hvr-hang:hover, .hvr-hang:focus, .hvr-hang:active {
  -webkit-animation-name: hvr-hang-sink, hvr-hang;
  animation-name: hvr-hang-sink, hvr-hang;
  -webkit-animation-duration: .3s, 1.5s;
  animation-duration: .3s, 1.5s;
  -webkit-animation-delay: 0s, .3s;
  animation-delay: 0s, .3s;
  -webkit-animation-timing-function: ease-out, ease-in-out;
  animation-timing-function: ease-out, ease-in-out;
  -webkit-animation-iteration-count: 1, infinite;
  animation-iteration-count: 1, infinite;
  -webkit-animation-fill-mode: forwards;
  animation-fill-mode: forwards;
  -webkit-animation-direction: normal, alternate;
  animation-direction: normal, alternate;
}
```

### Message 
I, Jennifer Adams, have read the point deduction list and understand that I will lose points for missing items.

### Image
![Univeristy of Florida Logo](https://identity.ufl.edu/wp-content/uploads/2015/10/Primary_card.jpg)