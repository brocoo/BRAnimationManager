# CADisplayLink+BRBlocksAddition

CADisplayLink is awesome.
Blocks are awesome.

CADisplayLink+BRBlocksAddition is a category on CADisplayLink that makes it support blocks. Each block passed is stored and performed on the main thread at each frame display (around 60 frames per second).

This comes in handy when you want to perform frame-by-frame like animations for non-animatable properties and objects, such as the text property of a UILabel.

## Installation

(Waiting to be published on Cocoapods)

## Usage

1.  Import the `CADisplayLink+BRBlocksAddition` category:

  ```objective-c
    #import "CADisplayLink+BRBlocksAddition.h"
  ```

(Work in progress)
