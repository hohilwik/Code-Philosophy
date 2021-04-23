# Documentation Style Guide

Contents:

1.  Philosophy
	1.  Simplicity
	1.  Readable source text
	1.  Minimum viable documentation
	1.  Better is better than perfect
1.  Best Practices
	1.  Frequently Trim Documentation
	1.  Update Docs with code
	1.  Delete Dead Documentation
	1.  Documentation As Story Of Your Code
1.  Style
	1.  Document layout
	1.  Character line limit
	1.  Trailing whitespace
	1.  Headings
	    1.  ATX-style headings
	    1.  Add spacing to headings
	1.  Lists
	    1.  Use lazy numbering for long lists
	    1.  Nested list spacing
	1.  Code
    	1.  Inline
    	1.  Codeblocks
    	1.  Declare the language
    	1.  Escape newlines
    	1.  Nest codeblocks within lists
	1.  Links
	   	1.  Use informative Markdown link titles
	1.  Images
	1.  Prefer lists to tables
	1.  Strongly prefer Markdown to HTML
1.



# Philosophy

埏埴以為器，當其無，有器之用.

*Clay becomes pottery through craft, but it's the emptiness that makes a pot
useful.*

\- [Laozi](http://ctext.org/dictionary.pl?if=en&id=11602)


## Simplicity and Flexibility

* **Scalability and interoperability** are more important than a menagerie of
  unessential features. Scale comes from simplicity, speed, and ease.
  Interoperability comes from minimal, digestible content.

* **Fewer distractions** make for better writing and more productive reading.

* **New features should never interfere with the simplest use case** and should
  remain invisible to users who don't need them.


* **Minimizing context switching makes people happier.** Team members should be
  able to interact with documentation using the same tools they use to read and
  write code.

## Readable source text

* **Plain text not only suffices, it is superior**. Markdown itself is not
  essential to this formula, but it is the best and most widely supported
  solution right now. HTML is generally not encouraged.

* **Content and presentation should not mingle**. It should always be possible
  to ditch the renderer and read the essential information at source. Users
  should never have to touch the presentation layer if they don't want to.

* **Portability and future-proofing leave room for the unimagined integrations
  to come**, and are best achieved by keeping the source as human-readable as
  possible.

* **Static content is better than dynamic**, because content should not depend
  on the features of any one server. However, **fresh is better than stale**. We should
  strive to balance these needs.

## Minimum viable documentation

* **Docs thrive when they are treated like tests**: a necessary chore one learns
  to savor because it rewards over time.
  See [Best Practices](#Best_Practices).

* **Brief and utilitarian is better than long and exhaustive**. The vast
  majority of users need only a small fraction of the author's total knowledge,
  but they need it quickly and often. Same for your team members trying to write more code based on existing code by reading through the documentation.

## Better is better than perfect

* **Incremental improvement is better than prolonged debate**. Patience and
  tolerance of imperfection allow projects to evolve organically. Small improvements are better than no improvements.

# Best Practices

"Say what you mean, simply and directly." - [Brian Kernighan]
(https://en.wikipedia.org/wiki/The_Elements_of_Programming_Style)


## Frequently Trim  Documentation

A small set of fresh and accurate docs are better than a sprawling, loose
assembly of "documentation" in various states of disrepair.

Write short and useful documents. Cut out everything unnecessary, while also
making a habit of continually massaging and improving every doc to suit your
changing needs. **Docs work best when they are alive but frequently trimmed,
like a bonsai tree**.

I encourage team members to take ownership of their docs and keep
them up to date with the same zeal we keep our tests in good order. Strive for
this.

* Identify what you really need: release docs, API docs, testing guidelines.
* Delete cruft frequently and in small batches.

## Update docs with code

**Change your documentation in the same commit as the code change**. This keeps your
docs fresh, and is also a good place to explain to your reviewer what you're
doing.

A good reviewer can at least insist that docstrings, header files, README.md
files, and any other docs get updated alongside the changelist.

## Delete dead documentation

Dead docs are bad. They misinform, they slow down, they incite despair in
engineers and laziness in team leads. They set a precedent for leaving behind
messes in a code base. If your home is clean, most guests will be clean without
being asked.

Just like any big cleaning project, **it's easy to be overwhelmed**. If your
docs are in bad shape:

*   Take it slow, doc health is a gradual accumulation.
*   First delete what you're certain is wrong, ignore what's unclear.
*   Get your whole team involved. Devote time to quickly scan every doc and make
    a simple decision: Keep or delete?
*   Default to delete or leave behind if migrating. Stragglers can always be
    recovered.
*   Iterate.

## Prefer the good over the perfect

Your documentation should be as good as possible within a reasonable time frame.
The standards for a documentation review are different from the
standards for code reviews. Reviewers can and should ask for improvements, but
in general, the author should always be able to invoke the "Good Over Perfect
Rule". It's preferable to allow authors to quickly submit changes that improve
the document, instead of forcing rounds of review until it's "perfect". Docs are
never perfect, and tend to gradually improve as the team learns what they really
need to write down.

## Documentation is the story of your code

Writing excellent code doesn't end when your code compiles or even if your
test coverage reaches 100%. It's easy to write something a computer understands,
it's much harder to write something both a human and a computer understand. Your
mission as a Code Health-conscious programmer is to **write for humans first,
computers second.** Documentation is an important part of this skill.

There's a spectrum of engineering documentation that ranges from terse comments
to detailed prose:

1.  **Inline comments**: The primary purpose of inline comments is to provide
    information that the code itself cannot contain, such as why the code is
    there.

2.  **Method and class comments**:

    *   **Method API documentation**: The header / Javadoc / docstring
        comments that say what methods do and how to use them. This
        documentation is **the contract of how your code must behave**. The
        intended audience is future programmers who will use and modify your
        code.

        It is often reasonable to say that any behavior documented here should
        have a test verifying it. This documentation details what arguments the
        method takes, what it returns, any "gotchas" or restrictions, and what
        exceptions it can throw or errors it can return. It does not usually
        explain why code behaves a particular way unless that's relevant to a
        developer's understanding of how to use the method. "Why" explanations
        are for inline comments. Think in practical terms when writing method
        documentation: "This is a hammer. You use it to pound nails."

    *   **Module API documentation**: The header / Javadoc / docstring
        comments for a module or a whole file. This documentation gives a brief
        overview of what the module / file does and often gives a few short
        examples of how you might use the module / file.

        Examples are particularly relevant when there's several distinct ways to
        use the module (some advanced, some simple). Always list the simplest
        use case first.

3.  **README.md**: A good README.md orients the new user to the directory and
    points to more detailed explanation and user guides:
    * What is this directory intended to hold?
    * Which files should the developer look at first? Are some files an API?
    * Who maintains this directory and where I can learn more?

    See the [README.md guidelines](https://github.com/hohilwik/Code-Philosophy/blob/main/README%20Style%20Guide).

# Style

Much of what makes Markdown great is the ability to write plain text, and get
great formatted output as a result. To keep the slate clean for the next author,
your Markdown should be simple and consistent with the whole corpus wherever
possible.

Seek to balance three goals:

1. *Source text is readable and portable.*
2. *Markdown files are maintainable over time and by different people.*
3. *The syntax is simple and easy to remember.*

## Document layout

In general, most documents benefit from some variation of the following layout:

```markdown
# Document Title

Short introduction.

[Table Of Contents]

## Topic

Content.

## See also

* https://link-to-more-info
```

1.  `# Document Title`: The first heading should be a level one heading, and
    should ideally be the same or nearly the same as the filename. The first
    level one heading is used as the page `<title>`.

1.  `author`: *Optional*. If you'd like to claim ownership of the document or
    if you are very proud of it, add yourself under the title. However,
    revision history generally suffices.

1.  `Short introduction.` 1-3 sentences providing a high-level overview of the
    topic. Imagine yourself as a complete newbie, who landed on your "Extending
    Foo" doc and needs to know the most basic assumptions you take for granted.
    "What is Foo? Why would I extend it?"

1.  `[TOC]`: if you use hosting that supports table of contents, such as Gitiles,
    put `[TOC]` after the short introduction. See
    [`[TOC]` documentation](https://gerrit.googlesource.com/gitiles/+/master/Documentation/markdown.md#Table-of-contents).

1.  `## Topic`: The rest of your headings should start from level 2.

1.  `## See also`: Put miscellaneous links at the bottom for the user who wants
    to know more or didn't find what she needed.

## Character line limit

Obey project character line limit wherever possible. Long URLs and tables are
the usual suspects when breaking the rule. (Headings also can't be wrapped, but
it is encouraged to keep them short). Otherwise, wrap your text:

```markdown
Lorem ipsum dolor sit amet, nec eius volumus patrioque cu, nec et commodo
hendrerit, id nobis saperet fuisset ius.

*   Malorum moderatius vim eu. In vix dico persecuti. Te nam saperet percipitur
    interesset. See the [foo docs](https://gerrit.googlesource.com/gitiles/+/master/Documentation/markdown.md).
```

Often, inserting a newline before a long link preserves readability while
minimizing the overflow:

```markdown
Lorem ipsum dolor sit amet. See the
[foo docs](https://gerrit.googlesource.com/gitiles/+/master/Documentation/markdown.md)
for details.
```

## Trailing whitespace

Don't use trailing whitespace, use a trailing backslash.

The [CommonMark spec](http://spec.commonmark.org/0.20/#hard-line-breaks) decrees
that two spaces at the end of a line should insert a `<br />` tag. However, many
directories have a trailing whitespace presubmit check in place, and many IDEs
will clean it up anyway.

Best practice is to avoid the need for a `<br />` altogether. Markdown creates
paragraph tags for you simply with newlines: get used to that.

## Headings

### ATX-style headings

```markdown
## Heading 2
```

Headings with `=` or `-` underlines can be annoying to maintain and don't fit
with the rest of the heading syntax. The user has to ask: Does `---` mean H1 or
H2?

```markdown
Heading - do you remember what level? DO NOT DO THIS.
---------
```

### Add spacing to headings

Prefer spacing after `#` and newlines before and after:

```markdown
...text before.

# Heading 1

Text after...
```

Lack of spacing makes it a little harder to read in source:

```markdown
...text before.

#Heading 1
Text after... DO NOT DO THIS.
```

## Lists

### Use lazy numbering for long lists

Markdown is smart enough to let the resulting HTML render your numbered lists
correctly. For longer lists that may change, especially long nested lists, use
"lazy" numbering:

```markdown
1.  Foo.
1.  Bar.
    1.  Foofoo.
    1.  Barbar.
1.  Baz.
```

However, if the list is small and you don't anticipate changing it, prefer fully
numbered lists, because it's nicer to read in source:

```markdown
1.  Foo.
2.  Bar.
3.  Baz.
```

If you look at the raw of this doc itself, you will see that all the lists so far have used lazy numbering. Markdown will do the numbering for you.

### Nested list spacing

When nesting lists, use a 4 space indent for both numbered and bulleted lists:

```markdown
1.  2 spaces after a numbered list.
    4 space indent for wrapped text.
2.  2 spaces again.

*   3 spaces after a bullet.
    4 space indent for wrapped text.
    1.  2 spaces after a numbered list.
        8 space indent for the wrapped text of a nested list.
    2.  Looks nice, don't it?
*   3 spaces after a bullet.
```

The following works, but it's very messy:

```markdown
* One space,
with no indent for wrapped text.
     1. Irregular nesting... DO NOT DO THIS.
```

Even when there's no nesting, using the 4 space indent makes layout consistent
for wrapped text:

```markdown
*   Foo,
    wrapped.

1.  2 spaces
    and 4 space indenting.
2.  2 spaces again.
```

However, when lists are small, not nested, and a single line, one space can
suffice for both kinds of lists:

```markdown
* Foo
* Bar
* Baz.

1. Foo.
2. Bar.
```

## Code

### Inline

&#96;Backticks&#96; designate `inline code`, and will render all wrapped content
literally. Use them for short code quotations and field names:

```markdown
You'll want to run `really_cool_script.sh arg`.

Pay attention to the `foo_bar_whammy` field in that table.
```

Use inline code when referring to file types in an abstract sense, rather than a
specific file:

```markdown
Be sure to update your `README.md`!
```

Backticks are the most common approach for "escaping" Markdown metacharacters;
in most situations where escaping would be needed, code font just makes sense
anyway.

### Codeblocks

For code quotations longer than a single line, use a codeblock:

<pre>
```c
int Foo(int foo, float bar){
foo= foo-bar;
}
```
</pre>

#### Declare the language

It is best practice to explicitly declare the language, so that neither the
syntax highlighter nor the next editor must guess.

#### Indented codeblocks are sometimes cleaner

Four-space indenting is also interpreted as a codeblock. These can look
cleaner and be easier to read in source, but there is no way to specify the
language. Their use is encouraged when writing many short snippets:

```markdown
You'll need to run:

    bazel run :thing -- --foo

And then:

    bazel run :another_thing -- --bar

And again:

    bazel run :yet_again -- --baz
```

#### Escape newlines

Because most commandline snippets are intended to be copied and pasted directly
into a terminal, it's best practice to escape any newlines. Use a single
backslash at the end of the line:

<pre>
```shell
bazel run :target -- --flag --foo=longlonglonglonglongvalue \
--bar=anotherlonglonglonglonglonglonglonglonglonglongvalue
```
</pre>

#### Nest codeblocks within lists

If you need a codeblock within a list, make sure to indent it so as to not break
the list:

```markdown
*   Bullet.

    ```c++
    int foo;
    ```

*   Next bullet.
```

You can also create a nested code block with 4 spaces. Simply indent 4
additional spaces from the list indentation:

```markdown
*   Bullet.

        int foo;

*   Next bullet.
```

## Links

Long links make source Markdown difficult to read and break the 80 character
wrapping. **Wherever possible, shorten your links**.

### Use informative Markdown link titles

Markdown link syntax allows you to set a link title, just as HTML does. Use it
wisely.

Titling your links as "link" or "here" tells the reader precisely nothing when
quickly scanning your doc and is a waste of space:

```markdown
See the syntax guide for more info: [link](syntax_guide.md).
Or, check out the style guide [here](style_guide.md).
DO NOT DO THIS.
```

Instead, write the sentence naturally, then go back and wrap the most
appropriate phrase with the link:

```markdown
See the [syntax guide](syntax_guide.md) for more info.
Or, check out the [style guide](style_guide.md).
```

## Images

Use images sparingly, and prefer simple screenshots. This guide is designed
around the idea that plain text gets users down to the business of communication
faster with less reader distraction and author procrastination. However, it's
sometimes very helpful to show what you mean.

See [image syntax](https://gerrit.googlesource.com/gitiles/+/master/Documentation/markdown.md#Images).

## Prefer lists to tables

Any tables in your Markdown should be small. Complex, large tables are difficult
to read in source and most importantly, **a pain to modify later**.

```markdown
Fruit | Attribute | Notes
--- | --- | --- | ---
Apple | [Juicy](https://example.com/SomeReallyReallyReallyReallyReallyReallyReallyReallyLongQuery), Firm, Sweet | Apples keep doctors away.
Banana | [Convenient](https://example.com/SomeDifferentReallyReallyReallyReallyReallyReallyReallyReallyLongQuery), Soft, Sweet | Contrary to popular belief, most apes prefer mangoes.

DO NOT DO THIS
```

[Lists](#lists) and subheadings usually suffice to present the same information
in a slightly less compact, though much more edit-friendly way:

```markdown
## Fruits

### Apple

* [Juicy](https://SomeReallyReallyReallyReallyReallyReallyReallyReallyReallyReallyReallyReallyReallyReallyReallyReallyLongURL)
* Firm
* Sweet

Apples keep doctors away.

### Banana

* [Convenient](https://example.com/SomeDifferentReallyReallyReallyReallyReallyReallyReallyReallyLongQuery)
* Soft
* Sweet

Contrary to popular belief, most apes prefer mangoes.
```

However, there are times when a small table is called for:

```markdown
Transport | Favored by | Advantages
--- | --- | ---
Swallow | Coconuts | Otherwise unladen
Bicycle | Miss Gulch | Weatherproof
X-34 landspeeder | Whiny farmboys | Cheap since the X-38 came out
```

## Strongly prefer Markdown to HTML

Please prefer standard Markdown syntax wherever possible and avoid HTML hacks.
If you can't seem to accomplish what you want, reconsider whether you really
need it. Except for [big tables](#prefer-lists-to-tables), Markdown meets almost
all needs already.

Every bit of HTML or Javascript hacking reduces the readability and portability.
This in turn limits the usefulness of integrations with
other tools, which may either present the source as plain text or render it. See
[Philosophy](#Philosophy).

While Github renders HTML, Gitiles does not, which should be reason enough to not use HTML or HTML syntax in documentation.
