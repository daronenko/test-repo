# Heading level 1

## Heading level 2

### Heading level 3

### Heading level 4

#### Heading level 5

##### Heading level 6

Heading level 1
==

Heading level 2
--

Paragraphs
--

    I really like to use a Markdown!

    I think I'll use it to format all of my documents from now on.

#### Output:

I really like to use a Markdown!

I think I'll use it to format all of my documents from now on.

Line Breaks
--

    This is the first line.<br>
    And this is the second line.

#### Output:

This is the first line.<br>
And this is the second line.

Emphasis
--

    Italicized text is the *cat's meow*.<br>
    I just love **bold text**.<br>
    This text is ***really important***.<br>

#### Output:

Italicized text is the *cat's meow*.<br>
I just love **bold text**.<br>
This text is ***really important***.<br>

Blockquotes
--

    > Dorothy followed her through many of the beautiful rooms in her castle.

#### Output:

> Dorothy followed her through many of the beautiful rooms in her castle.

Blockquotes with Multiple Paragraphs
--

    > Dorothy followed her through many of the beautiful rooms in her castle.
    >
    > The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

#### Output:

> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

Nested Blockquotes
--

    > Dorothy followed her through many of the beautiful rooms in her castle.
    >
    >> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

#### Output:

> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

Blockquotes with Other Elements
--

    > #### The quarterly results look great!
    >
    > - Revenue was off the chart.
    > - Profits were higher than ever.
    >
    >  *Everything* is going according to **plan**.

#### Output:

> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.

Ordered Lists
--

    1. First item
    2. Second item
    3. Third item
        1. Indented item
        2. Indented item
    4. Fourth item

#### Output:

1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item

Unordered Lists
--

    - First item
    - 2\. item
    - Third item
        - Indented item
        - Indented item
    - Fourth item

#### Output:

- First item
- 2\. item
- Third item
    - Indented item
    - Indented item
- Fourth item

Adding Elements in Lists
--

    - This is the first list item.
    - Here's the second list item.

        I need to add another paragraph below the second list item.<br>
        > A blockquote would look great below the second list item.<br>
        ![Tux, the Linux mascot](/tux.avif)

    - And here's the third list item.

#### Output:

- This is the first list item.

    1. First item
    2. Second item
    3. Third item

- Here's the second list item.

    I need to add another paragraph below the second list item.<br>
    
    > A blockquote would look great below the second list item.<br>
    
    ![Tux, the Linux mascot](/tux.avif)

- And here's the third list item.

Code
--

    At the command prompt, type `nano`.

#### Output:

At the command prompt, type `nano`.

Code Blocks
--

    ```html
    <html>
      <head>
      </head>
    </html>
    ```

#### Output:

```html
<html>
  <head>
  </head>
</html>
```

Horizontal Rules
--

    ---

#### Output:

---

Links
--

    My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").
    
#### Output:

My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

URLs and Email Addresses
--

    <https://www.markdownguide.org><br>
    <fake@example.com>

#### Output:

<https://www.markdownguide.org><br>
<fake@example.com>

Formatting Links
--

    I love supporting the **[EFF](https://eff.org)**.<br>
    This is the *[Markdown Guide](https://www.markdownguide.org)*.<br>
    See the section on [`code`](#code).

#### Output:

I love supporting the **[EFF](https://eff.org)**.<br>
This is the *[Markdown Guide](https://www.markdownguide.org)*.<br>
See the section on [`code`](#code).

Linking Images
--

    [![An old rock in the desert](/tux.avif "Shiprock, New Mexico by Beau Rogers")](https://github.com/)

#### Output:

[![An old rock in the desert](/tux.avif "Shiprock, New Mexico by Beau Rogers")](https://github.com/)

Escaping Characters
--

    \* Without the backslash, this would be a bullet in an unordered list.

#### Output:

\* Without the backslash, this would be a bullet in an unordered list.
