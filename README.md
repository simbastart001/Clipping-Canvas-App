# Clipping Canvas App

This Android app demonstrates various clipping techniques using the Canvas API. The `ClippedView` class provides examples of different clipping scenarios, showcasing how to use clipping rectangles, circles, paths, and more.

## Features

- Clipped rectangles
- Difference clipping example
- Circular clipping example
- Intersection clipping example
- Combined clipping example
- Rounded rectangle clipping example
- Outside clipping example
- Translated text example
- Skewed text example
- Quick reject example

## Usage

The main functionality is implemented in the `ClippedView` class, and the app's main activity (`MainActivity`) sets the content view to an instance of this view.

```kotlin
class MainActivity : AppCompatActivity() {
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(ClippedView(this))
    }
}
