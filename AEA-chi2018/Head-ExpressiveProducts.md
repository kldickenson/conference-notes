# Building More Expressive Products - Val Head

Unified expression via
Type, copy, color, layout, motion, sound,...

Styling with motion
Easing choices
Duration
Properties that are animated

Start with a simple circle on the screen to test out.

## Expressing personality with Motion

### Calm, soft, reassuring: 
Opacities, soft blurs, small deltas, 
easing curves with gradual speed changes

Transition:
```css
Filter 200ms $ease-in-quad;
Opacity: 150ms 50ms $ease-in-quad
```

Calm suggestions:
EaseInSine, easeOutSine, easeInOutQuad

### Confident, Stable, Strong

Direct movements, straight lines, symmetrical ease-in-outs

Avoid blurs, bounces, or overshadows

EaseInCubic, easeOutCubic, easeInOutCubic

EaseInQuart, easeOutQuart, easeInOutQuart


### Lively, Energetic, Friendly

Overshoots, anticipation, "snappy" easing curves

Try anticipation + overshoot!

EaseInBack, easeOutBack, easeInOutBack

#### Using keyframes
For more control of the overshoot. Use a different

### Playful, fun, Lighthearted
Bounces, shapes morphs, squash and stretch

These effects CANNOT been done with Cubic Beziers.

[GreenSock Ease Visualizer](URL)

## Expressing personality with Sound

The smaller the screen size, the more you need to use sound for auditive and tactile display

What makes sound annoying:

* Not appropriate for the situation
* Played at the wrong time
* Too loud
* Lack of user control

### What sound can offer design
Combining sound with animation (example: breathing app for meditation)

Sound is powerful brand differentiation

__Earcons__: an icon for the ears

* Alerts and notifications (when your attention may be elsewhere)
* Navigation Space
* Confirming Actions
* Marking positive moments (purchase completion, task completion)

Best practices for UI sounds:

* UI sounds should be short, \<400ms
* End on an ascending interval for positive feedback
* End on a descending inter for negative feedback
* Give the suer controls to stop/customize

[Emotional music](Howmusicreallyworks.com/Pages_Chapter_4/4_4.html)

[8ve/Octave]() for free sounds
[Motion Sounds]() $$ created by audio engineers

[Designing Interface Animation]()