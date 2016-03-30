---
layout: "default"
title: "Forms"
---

# Forms

Forms allow users to enter data that is used by the application, or to configure options. Designing forms well requires decisions about its structure and sequence, as well as its interface elements, field labels and offered help and feedback.

## Common recommendations

* Use a form layout that is appropriate for the content.
* Use the same style of label placement for all controls in a form.
* Use in-line place holder text when form content is simple or easily understood.
* Don't use multiple columns when there is extensive vertical panning.
* Don't place labels to the left when there is a lot of variance in the length of the labels.
* Don't place labels to the left when use multiple columns.

## Form details

![](https://idt.invisionapp.com/static-signed/live-embed/40012101/146653053/3/latest/HsPRtloTwYlEelE3ONrFSbKH2GrmmzKUh2c5Et9dAd5CMBh7MAowFqlELoKAZOhBn8jfZT6vqC5GZ0xnsMLipXGJglE/Form-details.png)

**1 - Form labels**: For labels use capitalized case. Default placement is above the field. Long labels should wrap and should not be truncated. Labels have bold font.

**2 - Checkbox and radio labels:** For checkboxes or radio buttons with long labels use sentence case. Only first line is bold in multiline labels, the rest lines are normal.

**3 - Optional field labels**: Most of the fields in our projects are mandatory. If all fields in the form are mandatory, don't provide any indication. If any field is optional mark it with `optional` label.

**4 - Form fields**: The length of the field should communicate the intended length of content. These lengths also apply for other form controls of a similar shape, like drop-down menus and text boxes.

**5 - Disabled fields**: Only show disabled fields if users need to know that the control might be available to them in other scenarios.

**Accessibility**: Auto focus the first field by default. Users should then be able to tab through elements in the form in a logical sequence.

## Label placement

Most controls need a label.

* Place labels above controls (default) or to the left of a control.
* Use the same style of label placement for all controls in a form.
* Place labels above controls when use multiple columns.

### When to use upper label placement

In general, place labels above controls. When using multi-column form layouts, always place labels above controls.

Placing labels above controls helps establish the relationship between a label and its control and helps create a clean layout, as all labels and controls can be left-aligned. Placing labels above controls makes it easier to present long strings and handle localization and accessibility issues.
Here are a two examples of upper label placement.

![](https://idt.invisionapp.com/static-signed/live-embed/40012101/146668323/1/latest/7efwtlwosDOLBAhaDQVceURZlECHY3jgHiCIjmsAoO4Rygf561FaFw0JxJtM944dzlEBTafkLlESoU27Ha2lEsOdQlE/Scheme-Labels-above.png)

### When to use left label placement

In single-column forms where vertical real estate must be conserved, place labels to the left of controls when:

* The label strings are short and approximately the same length.
* There is enough horizontal space for the longest label string (in any locale).

Here's an example of a form that uses left label placement:

![](https://idt.invisionapp.com/static-signed/live-embed/40012101/146932885/2/latest/6NgBM75hqndvyM9NW86zlEglE2PIwCd9yYhybUlEjjJ2IplEGprPsZtAo6Vg1lrtkrUthwYtk8zVpJzBe3fXf3lUIglE/Scheme-Labels-left.png)

Don't place labels to the left when there is a lot of variance in the length of the labels. Because some labels will be too far away from their controls or in case of wrapping labels will be taller than controls.

![](https://idt.invisionapp.com/static-signed/live-embed/40012101/146934317/5/latest/lETClEVQcI7CVRv9fkXVv7lEeETTplT7mtl6IeRLyr64PiVpTPg1IbkvzWH0dvlE1M49ezDthSZtMfM7mSnHLsit7AlE/Scheme-Labels-left-avoid.png)

Don't use left label placement in multi-column form layouts. The labels themselves might look like a separate column and labels in second column might have unintended visual relationship to controls from first column.

![](https://idt.invisionapp.com/static-signed/live-embed/40012101/146939218/1/latest/YlEkpsXWqHleONLE1BOWJ3cWvXZJqRudKwULdVMpQQPyGmxKsngQbMsEQJZIjkvB12uwSjF33HToRPdCTtCjazQlE/Scheme-Labels-left-avoid-2.png)

## Form layout

When you design a form and the control layout, think about how you want the user to fill out the form and the effects panning/scrolling might have on the experience. Make sure you also consider the impact of the touch keyboard (it can use up to 50% of the screen in landscape orientation) and inline error notifications, if used.

![](https://idt.invisionapp.com/static-signed/live-embed/40012101/145515818/13/latest/DuMg72YcHayEcxJ14tC9PfixKawvSRsSVRxo0BBnrcRiabmRmveFAQrjib1AchZK8wlAc0LF8oNawHbmXa1PyAlE/Register-form.png)

**1 - Form title**: Describes the form as a whole. If the form is the main item on a page, use an `h2` tag, otherwise use `h3` and adjust the rest of the page hierarchy accordingly. This can be followed by a short paragraph of text to introduce the form.

**2 - Form group headline**: Describes a group of controls and fields within a form that relate to each other and where users benefit from concentrating on them as a whole. Usually `h3`. This can be followed by a short paragraph of text to explain the group.

**3 - End of form line**: If the form has more than one form group or embed buttons, a line is necessary so users understand the form actions apply to the form as a whole.

**4 - Form buttons**: A form usually has a primary button for the main action, and a link button to cancel. The primary button is left aligned along with the left side of the form fields. If more actions are needed, put the primary button first, then any standard buttons, then the link button.

The only exception is a multi-step form where the *'Back'* standard button sits at the very left, while the rest of the buttons are aligned to right.

**Field order**: Group related fields and controls together. If one field impacts another field, always place it before the field it impacts.

### Single-column layouts

Use a single-column layout for your form when:

* You want to encourage users to fill out the form in a specific order.
* The form spans multiple pages.
* The window is resized to a tall, narrow layout.
* The screen displays additional notes and info, instructions, or branding and advertising.

Here's an example of a short form that uses a single-column layout:

![](https://idt.invisionapp.com/static-signed/live-embed/40012101/146967594/1/latest/FkR8DjyN25SuYzJObdfuZCLhYpONdttcRqlE9SlEo3NpkcDT02CcF34hygYeObfjlEJ57k4L7lErZONqufruAQHE6glE/Scheme-Single-column.png)

### When to use two-column layouts

Use a two-column layout for short forms with limited vertical panning. The two-column layout makes the best use of screen real estate in landscape orientation. Remember to reserve ample gutter space or divider line between the two columns.

Here's an example of a form that uses two columns:

![](https://idt.invisionapp.com/static-signed/live-embed/40012101/146968396/1/latest/knqyZb2pEdamMHszh3GSlEEY5spmVHtG846iCccMGLUOcPdC0O6owVuxcIdVWfsfWyZs3BdhZeWlEikZERQa0lEZwlE/Scheme-Multi-column.png)

Don't use multiple columns when there is extensive vertical panning. To fill out the form, the user has to reach the bottom of the first column, move to the top of the second column, and then back down again. This experience becomes even more cumbersome if the touch keyboard is displayed.

Here's an example of a form that uses two columns improperly:

![](https://idt.invisionapp.com/static-signed/live-embed/40012101/146973817/22/latest/EDl2lEg6b2wfNInklCy9LP66ylEQnHs5mcGLF8yIB4zlEKRr47oiFlEWWVbia8m1GkulExAUjlEZd1gsoaalEZ9MlEBhglE/Scheme-Multi-column-avoid.png)

## Designing long forms

When users access a form, it can be daunting to immediately see a large number of fields that need to be filled out. The threshold for when a form is considered 'too long' depends on the audience and the application context. There are various techniques of lessening the impact of long forms.

Here's an example of a longer form that uses a single-column layout:

![](https://msdn.microsoft.com/dynimg/IC631812.png)

Instead of trying to fit a lot of controls into one very long form, consider breaking up the task into groups or into a sequence of several forms. Here's an example of a longer form that is broken up into groups:

![](https://msdn.microsoft.com/dynimg/IC631813.png)

### Multi-step forms

The multipage form pattern shows a multi-step approach that can be used to spread form fields across more than one screen. Make sure each screen shows fields that logically belong together, and that move users forward through the larger form step by step. This pattern is also good for saving progress through a form along the way. However, make sure users know what has and has not been executed for them along the way.

Here's an example of a longer form that's broken up into multiple pages:

![](https://msdn.microsoft.com/dynimg/IC631814.png)

### Progressive disclosure

A form can reveal more content as users go through it and use fields and controls. This technique can be used when it is not necessary to see all controls unless users have made specific decisions (e.g. unless they checked a particular check box), or when a particular decision has to be made first before it would make sense to move forward in the form.

## Form help

Forms must be easy to fill out. Target users often need help to clarify what information is required from them. Provide help where needed but bear in mind that too much help can make the form look busy and difficult.

![](https://design.atlassian.com/images/forms/form-call-outs-03.png)

**1 - Placeholder text**: Informs users what they need to do to interact with the field (e.g. 'Start typing to see names'), or shows an example of a typical entry (for example, 'e.g. My first project'). Examples must start with 'e.g.' Only supply placeholder text where clarification is required, do not overuse it.

**2 - Field rules information and tooltip**: On focus of the field, or on click of the 'i', provide information within an inline dialog that explains the rules and restrictions of a form field (e.g. 'Passwords must be between 8-20 characters long'). Keep this text as short as possible. If rules are sophisticated, provide a link to more information within the inline dialog and open the link in a new browser tab.

**3 - Help indicator and tooltip**: The 'i' shows that there is information available that explains the meaning of a field in more detail. It triggers an inline dialog that can have a headline, paragraph text and actions. Do not overuse the help indicator. The 'i' icon should appear to the right of the field. If information is only relevant when entering data, omit the 'i', and trigger the inline dialog on field focus. If there is too much information to fit in the help indicator, a link should be provided to an external page (in a new browser tab) that provides additional information.

## Error and success – system feedback

![](https://design.atlassian.com/images/forms/form-call-outs-04.png)

**1 - Field error**: When a form or field submission fails, all fields responsible for the problem are shown with a red outline and an exclamation mark icon.

**2 - Field error message**: The error icon behavior is the same as the help icon (displayed on focus and on click of the icon). Error messages should be relevant to the user and human in their writing style. Do not stack error messages, but rather think about what users need to do to resolve the problem. In case the error is shown for a field that would otherwise have help text, write your message in a way that both explains the field and the error. If the error requires explanation in detail, a link should be provided to an external page (in a new browser tab). If the error explanation includes dynamic content, such as diagnostic information, it should be opened in a modal dialog.

**3 - Field success indicator**: Where inline validation happens immediately, a correctly filled out field shows a success icon.

### Form validation timing

**Real-time validation**: By default, fields will validate after the user loses focus and the field value has changed. If necessary, the field then shows a progress indicator and comes back either with a field success or error state. If the field validates successfully, an icon should only be displayed if it's beneficial for the user to know that the field value has validated (e.g. a unique username was entered).

**Full page validation**: Where real-time validation is not possible or doesn't make sense, all fields are validated at the same time on page submission. During page validation, the primary action button turns into a progress indicator. If fields have caused problems, all problematic fields are shown as field errors. The form will automatically focus on the first problematic field. If validation requires a full page reload, ensure that the first invalid field is focused when the page is loaded.

**Complete form success and error**: If necessary for user understanding, show a confirmation message at the top of the form (if the screen doesn't change) or the next page (if form submission moves users to another page) after successfully submitting it. Where it can't be identified exactly which fields have led to the form submission to fail, use an alert message. Make sure the message text helps users as much as possible to rectify the problem.

An effective way of preventing users from sending off an incomplete form is to disable the buttons at the end of the form until all mandatory fields have been filled out. Be aware though that this means users will not see error messages that might help them rectify problems.
