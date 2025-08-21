---
description: This is the page description
---

# Debug - Markdown test page

## Heading 1

### Header 2

#### Header 3

This is a paragraph

* This is an unordered list
  * This is the indent

1. This is an ordered list
   1. This is the indent
      1. Another one
         1. Another one

* [ ] This is a task

***

{% hint style="info" %}
This is an info box
{% endhint %}

{% hint style="info" %}
This is an info box with 2 lines

This is line 2
{% endhint %}

{% hint style="warning" %}
This is a warning box
{% endhint %}

{% hint style="danger" %}
This is a danger box
{% endhint %}

{% hint style="success" %}
This is a success box
{% endhint %}

> Here is a quote&#x20;

```
// Some code as plain text
```

```html
// Some code as html
```

<figure><img src=".gitbook/assets/webagent-overview.png" alt=""><figcaption></figcaption></figure>

| Column 1 | Column 2 |
| -------- | -------- |
| Row 1    | Value    |
| Row 2    | Value    |

Left align

<p align="center">Center</p>

<p align="right">Right align</p>

<table data-view="cards"><thead><tr><th></th><th></th><th data-type="checkbox"></th><th data-type="rating" data-max="5"></th><th data-type="users" data-multiple></th></tr></thead><tbody><tr><td>Card 1</td><td>With text</td><td>false</td><td>null</td><td></td></tr><tr><td>Card 2</td><td></td><td>true</td><td>4</td><td></td></tr></tbody></table>

<details>

<summary>Header of an expandable</summary>

Text of the expandable

</details>

{% tabs %}
{% tab title="First Tab" %}
Text of first tab
{% endtab %}

{% tab title="Second Tab" %}
Text of second tab
{% endtab %}
{% endtabs %}

{% stepper %}
{% step %}
### Step 1

Step 1 content
{% endstep %}

{% step %}
### Step 2

Step 2 content
{% endstep %}
{% endstepper %}

{% columns %}
{% column %}
First column
{% endcolumn %}

{% column %}
Second column
{% endcolumn %}
{% endcolumns %}

{% embed url="https://youtu.be/L0X3zZc45lo" %}

{% content-ref url="webagent/getting-started/" %}
[getting-started](webagent/getting-started/)
{% endcontent-ref %}

Here is a link in the text [getting-started](webagent/getting-started/ "mention") to another page

Here is a link in the text [#heading-1](debug-markdown-test-page.md#heading-1 "mention") to the same page

Test <a href="debug-markdown-test-page.md#heading-1" class="button primary">New button</a>

Test <code class="expression"></code>This is an expression?

Test <i class="fa-jedi-order">:jedi-order:</i> icon

Test $$f(x) = x * e^{2 pi i \xi x}$$ math

Test ![](.gitbook/assets/webagent-overview.png) inline image
