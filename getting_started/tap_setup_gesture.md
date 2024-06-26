# Setting up a new Gesture

We will now set up a new gesture. Let's start with by clicking the `Setup a new Gesture` button.
(or the `+` button in the top right corner)

```{figure} img/gesture_selection_screen.png
:alt: Gesture Selection Screen
:width: 100%
```

Here you will see a list of all the gestures that are available to set up. \
You can search for a specific gesture by typing in the search bar at the top.

## Setting up a simple Tap Gesture

For this example, we will set up the most basic gesture, a single touch **Tap**. \
A **Tap** will momentarily press a specified Binding.

```{note}
A Binding is a key, mouse button, or any actions that may be triggered by another plugin.
```

Click on the **Tap** gesture to proceed.

### Options

```{figure} img/tap_setup_screen_options.png
:alt: Tap Setup Screen (Options Part)
:width: 100%
```

You are now on the first part of the setup screen. Here you can configure the option for the **Tap** gesture. \
The option in question for this gesture is the number of touches required to trigger the gesture.

```{figure} img/tap_setup_screen_options_dropdown.png
:alt: Tap Setup Screen (Options Part - Dropdown)
:align: center
```

Let's keep this number at `1` for now. \
Click on the `Next` button to proceed.

### Binding

```{figure} img/tap_setup_screen_binding.png
:alt: Tap Setup Screen (Binding Part)
:width: 100%
```

You are now on the second part of the setup screen. \
Here you can configure the Binding that will be triggered by the **Tap** gesture.

```{note}
A Binding is a key, mouse button, or any actions that may be triggered by another plugin.
```

This interface should be familiar to you if you have used OpenTabletDriver before:
The large button will open the simple binding editor, 
while the small button containing `...` will open the advanced binding editor.

For this example, we will use the simple binding editor. \
Click on the large button to proceed.

```{figure} img/binding_editor_simple.png
:alt: Simple Binding Editor
:align: center
```

Here you can press most keys on your keyboard, or click on the mouse buttons to select them. \
For this example, let's left click within the white outlined area. \
Once that's done, the window will close, and the Binding will appear in the Binding Display.

```{figure} img/tap_setup_screen_binding_set.png
:alt: Tap Setup Screen (Binding Part - Set)
```

Let's proceed with the final part of the setup by clicking on `Next` again.

### Boundaries & Additional Tweaks

```{figure} img/tap_setup_screen_tweaks.png
:alt: Tap Setup Screen (Tweaks Part)
:width: 100%
```

You are now on the final part of the setup screen. \
Here you can configure the boundaries and additional tweaks for the **Tap** gesture.

Again, if you have used OpenTabletDriver before, you have probably setup your area in a specific way. \
Here however, it is slightly different, as a gesture may only be trigerred if it is started within the specified area.

```{warning}
The boundaries size must be non-zero.
```

let's keep it at the default values for now and focus on the only available tweak for this gesture: \
The `Deadline` tweak.

If you hover your cursor over the tweak, you will see a tooltip explaining what it does. \
In this case, the `Deadline` represents the amount of time within which the gesture must be completed. \
This include the you put your finger down, until it is lifted up again.

80ms is the default value, but you can change it to your liking.

```{note}
This value was chosen as it was the average accross all Wacom CTH-xxx & PTH-x51 tablets.
```

When you are done, click on the `Complete` button to finish the setup.

```{figure} img/tap_gesture_overview_new.png
:alt: Gesture Overview - New Gesture Added
:width: 100%
```

Congratulations! You have successfully set up a new **Tap** gesture.

```{tip}
You may choose to save your configuration by clicking on the `Save` button in the bottom right corner.
```

We will now move on to the next step: Editing an existing Gesture.