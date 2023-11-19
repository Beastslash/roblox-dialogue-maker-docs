# Create and manage themes
You can make a theme by duplicating any theme in the Themes folder. For this tutorial, we can duplicate the `BigAndBoldDialogue` ScreenGui.

![15404527697](https://github.com/Beastslash/roblox-dialogue-maker-docs/assets/37517470/0cbe4d97-e9fc-4b34-a799-23be41066b2a)

## Theme GUI structure
As long as you follow the following structure, you can do just about anything:

* Theme (can be called anything) [must be ScreenGui]

  * DialogueContainer

    * NPCNameFrame

      * NPCName [must be TextLabel]

    * NPCTextContainerWithResponses

      * Segment [must be TextLabel]

    * NPCTextContainerWithoutResponses

      * Segment [must be TextLabel or TextButton]

    * ResponseContainer

      * ResponseTemplate [must be ScrollingFrame, for now]

    * ClickToContinue
