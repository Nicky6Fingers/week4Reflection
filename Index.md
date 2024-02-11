# Week 4 Reflections

## CSS Units Podcast Reflection

Let me start off by saying that at first glance HTML/CSs seems "simple". You can easily get a simple static website going with the more simple HTML tags, and in theory little to no CSS. But depending on how deep you dig, the functionality of the things you can do grows greatly. and the power of the tools for instance in the podcast it mentioned formatting **ill get into this more later** using rems and ems you are able to scale your website much easier *IF* the website was made with this initially in mind. And that is kind of the point i want to make, depending on your knowledge of certain things and if you created the website with these functions properly in the first place it makes things much easier to format and change. Without having to do it all again.

## Tailwind CSS

### Letter Spacing

**Definition:** *Control the letter spacing of an element using the tracking-{size} utilities.*

**HOW:**  `<p class="tracking-tight ...">The quick brown fox ...</p>
          <p class="tracking-normal ...">The quick brown fox ...</p>
          <p class="tracking-wide ...">The quick brown fox ...</p>*`

### Border Radius

**Definition** *Use utilities like rounded-sm, rounded, or rounded-lg to apply different border radius sizes to an element.*

**HOW:** `<div class="rounded ..."></div>
        <div class="rounded-md ..."></div>
        <div class="rounded-lg ..."></div>
        <div class="rounded-full ..."></div>`

### Block and Inline

**Definition:** *Use inline, inline-block, and block to control the flow of text and elements.*

**HOW:**
 When controlling the flow of text, using the CSS property
 `<span class="inline">display: inline</span>`
  will cause the text inside the element to wrap normally.

  While using the property `<span class="inline-block">display: inline-block</span>`
  will wrap the element to prevent the text inside from extending beyond its parent.

  Lastly, using the property `<span class="block">display: block</span>`
  will put the element on its own line and fill its parent.

### Grid Auto Flow

**Definition:** Use the grid-flow-{keyword} utilities to control how the auto-placement algorithm works for a grid layout.

**HOW:** `<div class="grid grid-flow-row-dense grid-cols-3 grid-rows-3 ...">`
 `<div class="col-span-2">01</div>`
  `<div class="col-span-2">02</div>`
  `<div>03</div>`
  `<div>04</div>`
  `<div>05</div>`
`</div>`

### Gap

**Definition:** Use gap-{size} to change the gap between both rows and columns in grid and flexbox layouts.

**HOW:** `<div class="grid gap-4 grid-cols-2">`
 `<div>01</div>`
  `<div>02</div>`
 `<div>03</div>`
 `<div>04</div>`
</div>
**Use gap-x-{size} and gap-y-{size} to change the gap between columns and rows independently**

### Greyscale

**Definition:** Use the grayscale and grayscale-0 utilities to control whether an element should be rendered as grayscale or in full color.

**HOW:** `<div class="grayscale-0 ...">`
  <!-- ... -->
`</div>`
`<div class="grayscale ...">`
  <!-- ... -->
`</div>`

### Scale

**Definition:** Use the scale-{percentage}, scale-x-{percentage}, and scale-y-{percentage} utilities to scale an element.

**HOW:** `<img class="scale-75 ...">`
`<img class="scale-100 ...">`
`<img class="scale-125 ...">`
`<img class="-scale-50">`
