```mermaid
classDiagram

    class Pixel {
        [Int: String] colorSet
        PixelSize size
        [[Int]] data
    }
    Pixel *--> PixelSize

    class PixelSize {
        Int width
        Int height
    }
```
