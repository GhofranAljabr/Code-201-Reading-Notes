# CSS Transforms, Transitions, and Animations
## CSS Transforms:
Transforms
In this Lesson7
CSS
Transform Syntax
2D Transforms
Combining Transforms
Transform Origin
Perspective
3D Transforms
Transform Style
Backface Visibility
SHARE
Share on Twitter
 
Share on Facebook
 
Share on Google+
With CSS3 came new ways to position and alter elements. Now general layout techniques can be revisited with alternative ways to size, position, and change elements. All of these new techniques are made possible by the transform property.

The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

Within this lesson we’ll take a look at both two-dimensional and three-dimensional transforms. Generally speaking, browser support for the transform property isn’t great, but it is getting better every day. For the best support vendor prefixes are encouraged, however you may need to download the nightly version of Chrome to see all of these transforms in action.

------------------------------------
## Transitions 

Transitions & Animations
In this Lesson8
CSS
Transitions
Shorthand Transitions
Animations
Customizing Animations
Shorthand Animations
SHARE
Share on Twitter
 
Share on Facebook
 
Share on Google+
ads via Carbon
Get busy earning as top freelance developer. Find out how much you can earn with Toptal.
ads via Carbon
One evolution with CSS3 was the ability to write behaviors for transitions and animations. Front end developers have been asking for the ability to design these interactions within HTML and CSS, without the use of JavaScript or Flash, for years. Now their wish has come true.

With CSS3 transitions you have the potential to alter the appearance and behavior of an element whenever a state change occurs, such as when it is hovered over, focused on, active, or targeted.

Animations within CSS3 allow the appearance and behavior of an element to be altered in multiple keyframes. Transitions provide a change from one state to another, while animations can set multiple points of transition upon different keyframes.

-----------------------

## Animations
Transitions do a great job of building out visual interactions from one state to another, and are perfect for these kinds of single state changes. However, when more control is required, transitions need to have multiple states. In return, this is where animations pick up where transitions leave off.

Animations Keyframes
To set multiple points at which an element should undergo a transition, use the @keyframes rule. The @keyframes rule includes the animation name, any animation breakpoints, and the properties intended to be animated.

`````````````
@keyframes slide {
  0% {
    left: 0;
    top: 0;
  }
  50% {
    left: 244px;
    top: 100px;
  }
  100% {
    left: 488px;
    top: 0;
  }
}
```````````````````````