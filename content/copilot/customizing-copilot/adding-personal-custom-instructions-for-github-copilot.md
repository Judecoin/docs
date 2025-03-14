---
title: Adding personal custom instructions for GitHub Copilot
shortTitle: Personal custom instructions
intro: 'You can add personal instructions for {% data variables.product.prodname_copilot_chat %} to customize chat responses for your conversations.'
versions:
  feature: copilot
topics:
  - Copilot
---

{% data reusables.copilot.personal-instructions-note %}

## About personal custom instructions for {% data variables.product.prodname_copilot_chat %}

You can add instructions for {% data variables.product.prodname_copilot_chat %} in order to receive chat responses that are customized to your personal preferences, across your conversations on the {% data variables.product.github %} website. Your saved instructions will not be displayed in the chat, but they are automatically provided to {% data variables.product.prodname_copilot_short %} so that it can provide responses aligned with your personal preferences.

For example, you can choose to always have {% data variables.product.prodname_copilot_chat_short %} respond in a preferred language or with a particular style. Some examples of instructions you could add are:
* `Always respond in Spanish.`
* `Your style is a helpful colleague, minimize explanations but provide enough context to understand the code.`
* `Always provide examples in TypeScript.`

Personal custom instructions apply to conversations that you, as a user, have with {% data variables.product.prodname_copilot_chat_short %} across {% data variables.product.github %}, and are different from repository custom instructions, which apply to conversations in the context of a single repository. For more information on repository instructions, see [AUTOTITLE](/copilot/customizing-copilot/adding-repository-custom-instructions-for-github-copilot).

{% data reusables.copilot.repository-vs-personal-instructions-note %} If you are concerned about response quality, you can also choose to temporarily disable repository instructions. See [AUTOTITLE](/copilot/customizing-copilot/adding-repository-custom-instructions-for-github-copilot?tool=webui#enabling-or-disabling-repository-custom-instructions).

## Adding personal custom instructions

You can add personal custom instructions either in the Chat panel or in immersive mode. The same instructions will be applied in both modes.

1. In the top right of any page on {% data variables.product.github %}, either:
   * Click the **{% octicon "copilot" aria-label="Copilot" %}** icon to open the {% data variables.product.prodname_copilot_chat_short %} panel.
   * Click {% octicon "triangle-down" aria-label="The downwards triangle icon" %} next to the **{% octicon "copilot" aria-label="Copilot" %}** icon, then click **Immersive** to open {% data variables.product.prodname_copilot_chat_short %} in the full-page, immersive mode.
1. Select the {% octicon "kebab-horizontal" aria-label="Open conversation options" %} dropdown menu at the top right of the Chat panel, or immersive page, then click **Personal instructions**.
1. Add natural language instructions to the text box.

   You can write your instructions in any format you prefer. For example, you can write them as a single block of text, each on a new line, or separated by blank lines.

1. Click **Save**. Your instructions are now active, and will stay active until you change or remove them.
