---
layout: layout.njk
title: MDN Color Palette
tags: color, design
---

# {{ title }}

Below follows the official [MDN Web Docs](https://developer.mozilla.org/) color palette. Also included below is the relevant `hex` or `RGB` color codes as well as the relevant `scss` variable names. Even though the `hex`/`rgb` codes are provided, always use the `scss` variable names unless indicated differently.

Below are also approved color combinations to ensure we always meet at least an `AA` (mid range) accessibility color contrast level.

<ul class="color-palette">
    <li class="color-palette-entry">
        <div class="swatch brand-primary"></div>
        <ul class="color-definitions">
            <li><code>$brand-primary</code></li>
            <li><code>#015fdf</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch blue"></div>
        <ul class="color-definitions">
            <li><code>$blue</code></li>
            <li><code>#3d7e9a</code></li>
            <li><b>note:</b> same as <code>$brand-primary-200</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch blue-light"></div>
        <ul class="color-definitions">
            <li><code>$blue-light</code></li>
            <li><code>#e4f0f5</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch blue-dark"></div>
        <ul class="color-definitions">
            <li><code>$blue-dark</code></li>
            <li><code>mix($blue, $blue-vdark, 65)</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch blue-vdark"></div>
        <ul class="color-definitions">
            <li><code>$blue-vdark</code></li>
            <li><code>#001d33</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch brand-primary-200"></div>
        <ul class="color-definitions">
            <li><code>$brand-primary-200</code></li>
            <li><code>#3d7e9a</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch brand-primary-300"></div>
        <ul class="color-definitions">
            <li><code>$brand-primary-300</code></li>
            <li><code>#3c7e9a</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch brand-primary-500"></div>
        <ul class="color-definitions">
            <li><code>$brand-primary-500</code></li>
            <li><code>#ebf4f7</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch brand-primary-600"></div>
        <ul class="color-definitions">
            <li><code>$brand-primary-600</code></li>
            <li><code>#f2f9ff</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch purple"></div>
        <ul class="color-definitions">
            <li><code>$purple</code></li>
            <li><code>#9198e5</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch purple-light"></div>
        <ul class="color-definitions">
            <li><code>$purple-light</code></li>
            <li><code>#d7d9f2</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch purple-dark"></div>
        <ul class="color-definitions">
            <li><code>$purple-dark</code></li>
            <li><code>mix($purple, $purple-vdark, 65)</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch purple-vdark"></div>
        <ul class="color-definitions">
            <li><code>$purple-vdark</code></li>
            <li><code>#303253</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch brand-red"></div>
        <ul class="color-definitions">
            <li><code>$brand-red</code></li>
            <li><code>#d65752</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch red"></div>
        <ul class="color-definitions">
            <li><code>$red</code></li>
            <li><code>#e66465</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch red-light"></div>
        <ul class="color-definitions">
            <li><code>$red-light</code></li>
            <li><code>#ffe7e8</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch red-dark"></div>
        <ul class="color-definitions">
            <li><code>$red-dark</code></li>
            <li><code>mix($red, $red-vdark, 65)</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch red-vdark"></div>
        <ul class="color-definitions">
            <li><code>$red-vdark</code></li>
            <li><code>#5d3739</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch orange"></div>
        <ul class="color-definitions">
            <li><code>$orange</code></li>
            <li><code>#f69d3c</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch orange-light"></div>
        <ul class="color-definitions">
            <li><code>$orange-light</code></li>
            <li><code>#ffe8d4</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch orange-dark"></div>
        <ul class="color-definitions">
            <li><code>$orange-dark</code></li>
            <li><code>mix($orange, $orange-vdark, 65)</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch orange-vdark"></div>
        <ul class="color-definitions">
            <li><code>$orange-vdark</code></li>
            <li><code>#332206</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch yellow"></div>
        <ul class="color-definitions">
            <li><code>$yellow</code></li>
            <li><code>#f6b73c</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch yellow-light"></div>
        <ul class="color-definitions">
            <li><code>$yellow-light</code></li>
            <li><code>#fff3d4</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch yellow-dark"></div>
        <ul class="color-definitions">
            <li><code>$yellow-dark</code></li>
            <li><code>mix($yellow, $yellow-vdark, 65)</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch yellow-vdark"></div>
        <ul class="color-definitions">
            <li><code>$yellow-vdark</code></li>
            <li><code>#332807</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch brand-green"></div>
        <ul class="color-definitions">
            <li><code>$brand-green</code></li>
            <li><code>#4d9f0c</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch green"></div>
        <ul class="color-definitions">
            <li><code>$green</code></li>
            <li><code>#4d9f0c</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch green-light"></div>
        <ul class="color-definitions">
            <li><code>$green-light</code></li>
            <li><code>#ebf8e1</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch green-dark"></div>
        <ul class="color-definitions">
            <li><code>$green-dark</code></li>
            <li><code>mix($green, $green-vdark, 65)</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch green-vdark"></div>
        <ul class="color-definitions">
            <li><code>$green-vdark</code></li>
            <li><code>#162300</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch brand-grey"></div>
        <ul class="color-definitions">
            <li><code>$brand-grey</code></li>
            <li><code>#4d9f0c</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch grey"></div>
        <ul class="color-definitions">
            <li><code>$grey</code></li>
            <li><code>#696969</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch grey-light"></div>
        <ul class="color-definitions">
            <li><code>$grey-light</code></li>
            <li><code>#eee</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch grey-dark"></div>
        <ul class="color-definitions">
            <li><code>$grey-dark</code></li>
            <li><code>mix($grey, $grey-vdark, 65)</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch grey-vdark"></div>
        <ul class="color-definitions">
            <li><code>$grey-vdark</code></li>
            <li><code>#151515</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch blue-grey"></div>
        <ul class="color-definitions">
            <li><code>$blue-grey</code></li>
            <li><code>#dce3e5</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch light-blue-grey"></div>
        <ul class="color-definitions">
            <li><code>$light-blue-grey</code></li>
            <li><code>#a1b4ce</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch light-grey"></div>
        <ul class="color-definitions">
            <li><code>$light-grey</code></li>
            <li><code>#fdfdfd</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch link-color"></div>
        <ul class="color-definitions">
            <li><code>$link-color</code></li>
            <li><code>#3d7e9a</code></li>
            <li><b>note:</b> same as <code>$brand-primary-200</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch payment-faq-base-color"></div>
        <ul class="color-definitions">
            <li><code>$payment-faq-base-color</code></li>
            <li><code>#3143e2</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch menu-link-color"></div>
        <ul class="color-definitions">
            <li><code>$menu-link-color</code></li>
            <li><code>$text-color</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch border-color"></div>
        <ul class="color-definitions">
            <li><code>$border-color</code></li>
            <li><code>#585858</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch light-border-color"></div>
        <ul class="color-definitions">
            <li><code>$light-border-color</code></li>
            <li><code>scale-color($border-color, $lightness: 70%)</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch warning-border-color"></div>
        <ul class="color-definitions">
            <li><code>$warning-border-color</code></li>
            <li><code>#ffc543</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch warning-background-color"></div>
        <ul class="color-definitions">
            <li><code>$warning-background-color</code></li>
            <li><code>scale-color($warning-border-color, $lightness: 50%);</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch warning"></div>
        <ul class="color-definitions">
            <li><code>$warning</code></li>
            <li><code>$yellow</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch negative"></div>
        <ul class="color-definitions">
            <li><code>$negative</code></li>
            <li><code>$red</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch error"></div>
        <ul class="color-definitions">
            <li><code>$error</code></li>
            <li><code>#900</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch positive"></div>
        <ul class="color-definitions">
            <li><code>$positive</code></li>
            <li><code>$green</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch neutral"></div>
        <ul class="color-definitions">
            <li><code>$neutral</code></li>
            <li><code>$blue</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch default"></div>
        <ul class="color-definitions">
            <li><code>$default</code></li>
            <li><code>$grey</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch accent-light"></div>
        <ul class="color-definitions">
            <li><code>$accent-light</code></li>
            <li><code>#83d0f2</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch accent-dark"></div>
        <ul class="color-definitions">
            <li><code>$accent-dark</code></li>
            <li><code>#216684</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch blue-background-text-color"></div>
        <ul class="color-definitions">
            <li><code>$blue-background-text-color</code></li>
            <li><code>#fff</code></li>
        </ul>
    </li>
</ul>

## Typography

<ul class="color-palette">
    <li class="color-palette-entry">
        <div class="swatch text-color"></div>
        <ul class="color-definitions">
            <li><code>$text-color</code></li>
            <li><code>#333</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch text-light"></div>
        <ul class="color-definitions">
            <li><code>$text-light</code></li>
            <li><code>#fff</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch text-dark"></div>
        <ul class="color-definitions">
            <li><code>$text-dark</code></li>
            <li><code>$text-color</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch user-head-secondary-text-color"></div>
        <ul class="color-definitions">
            <li><code>$user-head-secondary-text-color</code></li>
            <li><code>#a19f93</code></li>
        </ul>
    </li>
</ul>

## Background Colors

<ul class="color-palette">
    <li class="color-palette-entry">
        <div class="swatch bg-dark"></div>
        <ul class="color-definitions">
            <li><code>$bg-dark</code></li>
            <li><code>#222</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch bg-good"></div>
        <ul class="color-definitions">
            <li><code>$bg-good</code></li>
            <li><code>mix($positive, #fff, 5%)</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch bg-bad"></div>
        <ul class="color-definitions">
            <li><code>$bg-bad</code></li>
            <li><code>mix($negative, #fff, 5%)</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch light-background-color"></div>
        <ul class="color-definitions">
            <li><code>$light-background-color</code></li>
            <li><code>#{map-get(map-get($colors-lookup, "default"), "light")}</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch header-background-color"></div>
        <ul class="color-definitions">
            <li><code>$header-background-color</code></li>
            <li><code>$light-background-color</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch code-block-background-color"></div>
        <ul class="color-definitions">
            <li><code>$code-block-background-color</code></li>
            <li><code>#{map-get(map-get($colors-lookup, "default"), "light")}</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch code-block-background-alt-color"></div>
        <ul class="color-definitions">
            <li><code>$code-block-background-alt-color</code></li>
            <li><code>#{map-get(map-get($colors-lookup, "neutral"), "light")}</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch toc-background-color"></div>
        <ul class="color-definitions">
            <li><code>$toc-background-color</code></li>
            <li><code>#fcfcfc</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch main-nav-box-shadow-color"></div>
        <ul class="color-definitions">
            <li><code>$main-nav-box-shadow-color</code></li>
            <li><code>rgba(12, 12, 13, 0.1)</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch main-menu-item-background-color"></div>
        <ul class="color-definitions">
            <li><code>$main-menu-item-background-color</code></li>
            <li><code>#3d7e9a</code></li>
            <li><b>note:</b> same as <code>$brand-primary-200</code></li>
        </ul>
    </li>
</ul>

## Border Colors

<ul class="color-palette">
    <li class="color-palette-entry">
        <div class="swatch code-block-border-color"></div>
        <ul class="color-definitions">
            <li><code>$code-block-border-color</code></li>
            <li><code>#{map-get(map-get($colors-lookup, "neutral"), "medium")}</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch toc-border-color"></div>
        <ul class="color-definitions">
            <li><code>$toc-border-color</code></li>
            <li><code>#dce3e5</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch box-border-hover-color"></div>
        <ul class="color-definitions">
            <li><code>$box-border-hover-color</code></li>
            <li><code>#25a</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch tag-border-color"></div>
        <ul class="color-definitions">
            <li><code>$tag-border-color</code></li>
            <li><code>#cee9f9</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch main-menu-border-color"></div>
        <ul class="color-definitions">
            <li><code>$main-menu-border-color</code></li>
            <li><code>#d8dfe2</code></li>
        </ul>
    </li>
</ul>

## Gradients

<ul class="color-palette">
    <li class="color-palette-entry">
        <div class="swatch toc-gradient-start-color"></div>
        <ul class="color-definitions">
            <li><code>$toc-gradient-start-color</code></li>
            <li><code>#206584</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch toc-gradient-end-color"></div>
        <ul class="color-definitions">
            <li><code>$toc-gradient-end-color</code></li>
            <li><code>#83d0f2</code></li>
            <li><b>note:</b> same as <code>$accent-light</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch payment-background-gradient"></div>
        <ul class="color-definitions">
            <li><code>$payment-background-gradient</code></li>
            <li><code>linear-gradient(to right, nth($payment-background-colors, 1), nth($payment-background-colors, 2));</code></li>
        </ul>
    </li>
</ul>

## Tables

<ul class="color-palette">
    <li class="color-palette-entry">
        <div class="swatch table-blue"></div>
        <ul class="color-definitions">
            <li><code>$table-blue</code></li>
            <li><code>#d4dde4</code></li>
        </ul>
    </li>
</ul>

## Forms

<ul class="color-palette">
    <li class="color-palette-entry">
        <div class="swatch form-border-color"></div>
        <ul class="color-definitions">
            <li><code>$form-border-color</code></li>
            <li><code>#9b9b9b</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch placeholder-text"></div>
        <ul class="color-definitions">
            <li><code>$placeholder-text</code></li>
            <li><code>lighten($form-border-color, 2)</code></li>
        </ul>
    </li>
</ul>

## Buttons

<ul class="color-palette">
    <li class="color-palette-entry">
        <div class="swatch cta-deep-blue"></div>
        <ul class="color-definitions">
            <li><code>$cta-deep-blue</code></li>
            <li><code>#161e65</code></li>
        </ul>
    </li>
</ul>

## Browser Compat Tables

<ul class="color-palette">
    <li class="color-palette-entry">
        <div class="swatch bc-colors-yes"></div>
        <ul class="color-definitions">
            <li><code>nth($bc-colors, 1)</code></li>
            <li><code>#e4f8e1</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch bc-colors-no"></div>
        <ul class="color-definitions">
            <li><code>nth($bc-colors, 2)</code></li>
            <li><code>#f8e1e1</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch bc-colors-partial"></div>
        <ul class="color-definitions">
            <li><code>nth($bc-colors, 3)</code></li>
            <li><code>$yellow-light</code></li>
        </ul>
    </li>
    <li class="color-palette-entry">
        <div class="swatch bc-colors-unknown"></div>
        <ul class="color-definitions">
            <li><code>nth($bc-colors, 4)</code></li>
            <li><code>$grey-light</code></li>
        </ul>
    </li>
</ul>
