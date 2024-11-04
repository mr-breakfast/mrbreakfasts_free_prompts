# Theming
Is there something about the icons you'd like to change? Details like color, font, drop shadow, and outline thickness are easy to change (although there are a few exceptions with the d-pad and mouse icons with their outline thickness).

I used Inkscape to make the icons, and I'll use to Inkscape to demonstrate. If you've used Inkscape before, hopefully these instructions are obvious.

## Changing the Color
All the colors in the icons are built with Inkscape's [gradient tool](https://inkscape-manuals.readthedocs.io/en/latest/creating-gradients.html). With the lock on, the changes to the gradients will be universally applied to every icon that uses the gradient. This will allow for easy editing as there are only a few gradients.

Here's a list of current gradients in use:

| Gradient Name | Use | Example |
| --- | --- | --- |
| `buttons_dark` | The background and drop shadow of dark style buttons | <img src="https://github.com/lopopylopy/mrbreakfasts_free_prompts/blob/main/png/button_dark.png" alt="button_dark"/> |
| `outline_dark` | The outline that surrounds the dark style buttons and keys | <img src="https://github.com/lopopylopy/mrbreakfasts_free_prompts/blob/main/png/button_dark.png" alt="button_dark"/> |
| `text_dark` | The text inside dark style buttons and keys | <img src="https://github.com/lopopylopy/mrbreakfasts_free_prompts/blob/main/png/a_dark.png" alt="a_dark"/> |
| `keys_dark` | The background, drop shadow, and highlight of dark style keys | <img src="https://github.com/lopopylopy/mrbreakfasts_free_prompts/blob/main/png/a_key_dark.png" alt="a_key_dark"/> |


By changing the colors of the gradient's stops, you can edit the colors of all the icons.

<img src="https://github.com/lopopylopy/mrbreakfasts_free_prompts/blob/main/docs/meta/gradient_stop.png" alt="gradient stop"/>

Select the stop and then change it's color. Here's the `buttons_light` gradient for example.

<img src="https://github.com/lopopylopy/mrbreakfasts_free_prompts/blob/main/docs/meta/edit_stop_color.png" alt="gradient stop color editing"/>

Changing the first stop will alter the color of the background. Changing the second will alter the color of the shadow. If you don't want a shadow, change the shadow color to the same color as the background.

Here's an example:

<img src="https://github.com/lopopylopy/mrbreakfasts_free_prompts/blob/main/docs/meta/button_after_editing_stops.png" alt="button_after_editing_stops"/>

### Editing the Drop Shadow
