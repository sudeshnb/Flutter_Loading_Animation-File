# Flutter Loading Animation

How to use

All loading animation APIs are same straight forward. There is a static method for each animation inside `LoadingAnimationWidget` class, which returns the Object of that animation. Both `size` and `color` are required some animations need more than one color.

Loading animation with one color
```dart
Scaffold(
    body: Center(
      child: LoadingAnimationWidget.staggeredDotWave(
        color: Colors.white,
        size: 200,
      ),
    )
```
Loading animation with more than one color. You have to provide both required colors.
```dart
Scaffold(
    body: Center(
        child: LoadingAnimationWidget.twistingDots(
          leftDotColor: const Color(0xFF1A1A3F),
          rightDotColor: const Color(0xFFEA3799),
          size: 200,
        ),
      ),
```
# Screen recordings with design credits

| ink Drop  | Wave Dots | Twisting Dots | Three Rotating Dots |
| ------------- | ------------- | ------------- | ------------- |
| <img src='https://raw.githubusercontent.com/watery-desert/assets/main/loading_animation_widget/inkDrop.gif' width='100'>  | <img src='https://raw.githubusercontent.com/watery-desert/assets/main/loading_animation_widget/waveDots.gif' width='100'>  |  <img src='https://raw.githubusercontent.com/watery-desert/assets/main/loading_animation_widget/twistingDots.gif' width='100'>  |  <img src='https://raw.githubusercontent.com/watery-desert/assets/main/loading_animation_widget/threeRotatingDots.gif' width='100'>  |
| Staggered Wave Dots  | Four Rotating Dots | Falling Dot | Progressive Dots |
| <img src='https://raw.githubusercontent.com/watery-desert/assets/main/loading_animation_widget/staggeredDotsWave.gif' width='100'>  | <img src='https://raw.githubusercontent.com/watery-desert/assets/main/loading_animation_widget/fourRotatingDots.gif' width='100'>  |  <img src='https://raw.githubusercontent.com/watery-desert/assets/main/loading_animation_widget/fallingDot.gif' width='100'> |  <img src='https://raw.githubusercontent.com/watery-desert/assets/main/loading_animation_widget/progressiveDots.gif' width='100'>  |
| Discrete Circular  | Three Arched Circle | Bouncing Ballt | Flickr |
| <img src='https://raw.githubusercontent.com/watery-desert/assets/main/loading_animation_widget/discreteCircular.gif' width='100'>  | <img src='https://raw.githubusercontent.com/watery-desert/assets/main/loading_animation_widget/threeArchedCircle.gif' width='100'>  |  <img src='https://raw.githubusercontent.com/watery-desert/assets/main/loading_animation_widget/bouncingBall.gif' width='100'> |  <img src='https://raw.githubusercontent.com/watery-desert/assets/main/loading_animation_widget/flickr.gif' width='100'>  |
| Hexagon Dots  | Beat | Two Rotating Arc | Horizontal Rotating Dots |
| <img src='https://raw.githubusercontent.com/watery-desert/assets/main/loading_animation_widget/hexagonDots.gif' width='100'>  | <img src='https://raw.githubusercontent.com/watery-desert/assets/main/loading_animation_widget/beat.gif' width='100'>  |  <img src='https://raw.githubusercontent.com/watery-desert/assets/main/loading_animation_widget/twoRotatingArc.gif' width='100'> |  <img src='https://raw.githubusercontent.com/watery-desert/assets/main/loading_animation_widget/horizontalRotatingDots.gif' width='100'>  |
| New Ton Cradle  | Stretched Dots | Half Triangle Dot | Dots Triangle |
| <img src='https://raw.githubusercontent.com/watery-desert/assets/main/loading_animation_widget/newtonCradle.gif' width='100'>  | <img src='https://raw.githubusercontent.com/watery-desert/assets/main/loading_animation_widget/stretchedDots.gif' width='100'>  |  <img src='https://raw.githubusercontent.com/watery-desert/assets/main/loading_animation_widget/halfTriangleDot.gif' width='100'> |  <img src='https://raw.githubusercontent.com/watery-desert/assets/main/loading_animation_widget/dotsTriangle.gif' width='100'>  |


