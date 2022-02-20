---
title: "Example page"
---

# Expand problem

## Markdown vs. shortcodes

### Expand with markdown

{{% expand %}}

Some normal text...

- Some markdown
- with **bold** and _italic_ text

{{% button href="https://gohugo.io" %}}Some Button{{% /button %}}

{{% /expand %}}

### Expand with shortcodes

{{< expand >}}

Some normal text...

- Some markdown
- with **bold** and _italic_ text

{{% button href="https://gohugo.io" %}}Some Button{{% /button %}}

{{< /expand >}}

### Expand with markdown & shortcodes

{{< expand >}}

Some normal text...

{{< markdown >}}
- Some markdown
- with **bold** and _italic_ text
{{< /markdown >}}

{{% button href="https://gohugo.io" %}}Some Button{{% /button %}}

{{< /expand >}}

## Markdown vs. Mermaid

### Mermaid only

{{< mermaid >}}
graph LR
    A[Square Rect] -- Link text --> B((Circle))
    A --> C(Round Rect)
    B --> D{Rhombus}
    C --> D
{{< /mermaid >}}

### Expand with mermaid shortcode

{{< expand >}}

{{< mermaid >}}
graph LR
    A[Square Rect] -- Link text --> B((Circle))
    A --> C(Round Rect)
    B --> D{Rhombus}
    C --> D
{{< /mermaid >}}

{{< /expand >}}

### Expand with mermaid code fences

{{% expand %}}

```mermaid
graph LR
    A[Square Rect] -- Link text --> B((Circle))
    A --> C(Round Rect)
    B --> D{Rhombus}
    C --> D
```

{{% /expand %}}
