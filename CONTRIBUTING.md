# Contributors welcome!

WAYS TO CONTRIBUTE

1. **Make additions or revisions** to the Figma Community file
2. **Give feedback:** We are constantly working to improve the file, so whether you're enjoying the library or notice something is missing or needs revisions, let us know!
3. **Share:** If you find the file helpful, spread the word!


CONTRIBUTING WORKFLOW

1. Decide what you'd like to contribute by reviewing current open issues. If you'd like to contribute something that isn't covered by an existing issue, create an issue using the provided template. 
2. Copy the Community file and create your component(s) on a new page. Please follow design conventions described below.
3. Submit your file for review and fix any issues noted by the maintainer.
4. Your component(s) or revision(s) will be added to the community file. Thank you for your awesome work!


DESIGN CONVENTIONS

It is important to follow these design conventions so that we can maintain consistency throughout the library file.

To create a new component in Figma, start by inspecting the live component on mantine.dev. Your goal is to create a 1:1 pixel perfect mapping of the live component in Figma using Auto Layout and Variants. Ensure that all components are responsive.

Each of Mantine's component props should map directly to the names of the variant properties in Figma. Typically, variant properties are things like size, radius, etc. Additionally, most components need a "state" property, which serves to define what the component looks like during user interactions (for an input component, for example, values for the "state" property might be default, hover, active, and completed). Be sure to use boolean properties when applicable. 

Ensure that the text and color styles defined in the Community file are appplied to all new components. Use Mantine's Blue as the default accent color. 

All possible combinations of the variant properties need to be created for each component. 





