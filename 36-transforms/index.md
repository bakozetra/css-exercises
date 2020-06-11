# CSS exercise 36: Transforms

The `transform` property is a powerful way to change many aspects of an element, mainly through applying changes to the element's geometry.

Let's look a little deeper at `transform`.

1. Name the functions we can use in a `transform`'s value?
1. Why do we have to use separate functions, in order, and as values, e.g. `transform: scale(0.5) rotate(45deg);` when we could have had separate properties like: `transform-scale: 0.5;`, or `transform-rotate: 45deg`?
1. Often, we want to move the central pin or axis of the transform away from its default position. What property do we use to set that?
1. Why is it preferable to use `transform: translate()` rather than `position` and its associated properties?
1. When an element is translated / transformed, what happens to the flow of the document? Therefore, what layout method is `transform` similar to?
1. What problems can you run in to when overriding a `transform` in a more specific selector?
1. If we want to go 3D, we need to use another property to set the view over the scene. What is that property?
1. We can control what the transform uses in its calculations in terms of the box model. What property can we use to adjust this?

1 a) We can  use : translate , perspective , scale , skew  ,rotate and traslate3d.
1 b) We  can use transform becuse it have to work in specific order.It is depend on the order.
1 c) We use transform:translateX(50deg)
1 d)
1 e) this property doesn't affect the flow of other elements, so it appears as though the element being deleted shrinks away.
 we can use position: relative.

1 f) It  is preferable because

1 g) We use perspective(). 

1 k) We  can use :-transform-box :content-box 
                                  border-box
                                  padding-box
                                  view-box









