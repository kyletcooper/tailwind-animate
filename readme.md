# Tailwind Animate

A small plugin for Tailwind CSS to add enhanced animation capabilities.

## Animations

The plugin adds new animation options, which can be affected by using the `ease-` and `duration-` utilities.

```
animate-fade

animate-clip-to-t
animate-clip-to-r
animate-clip-to-b
animate-clip-to-l
```

## Easings

Use more dynamic easing functions.

```
ease-in-sine
ease-out-sine
ease-sine
ease-in-quad
ease-out-quad
ease-quad
ease-in-cubic
ease-out-cubic
ease-cubic
ease-in-quart
ease-out-quart
ease-quart
ease-in-expo
ease-out-expo
ease-expo
ease-in-back
ease-out-back
ease-back
```

## Parallax

Use the `parallax-y-` or `parallax-x-` classes to quickly add parallax effects using CSS View Timelines. The strength of movement corresponds to your theme's spacing scale.

## Delay

Set animation delays using the `animation-delay-` utility.

### Canon Effects

Tailwind Animate automatically tracks the index of sibling elements to they can be animated in sequence. Using the `animation-delay-canon-` utilities, animations are delayed until the previous sibling finishes.

## Fill Mode

Use `fill-fowards`, `fill-backwards` and `fill-both` to have your elements hold their styling before/after animations.

## Animation Direction

Use `animation-direction` to change the direction of animations.

## Animation Play State

Use `running` and `paused` to control the animation play state.
