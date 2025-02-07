# MappingComponents

Using .map function to render an array of objects by iterating and sending their props to the Card component, via a function receiving individual objects to render a card at a time. The "key" property needs to be included to make the iteration efficient, a redundant id property can be added to access the number of the object/card, since "key" is a special property that is unacessible via component props.


