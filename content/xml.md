---
layout: default
title: XML
nav_order: 5
---

# XML: A Very Brief Overview

In this workshop, we will be focusing on a markup language (and file format) called **XML**. XML stands for **eXtensible Markup Language**, which is similar in some ways to HTML and was designed to describe, store, and communicate information in a way that is readable to computers, while still human readable. 

**Why XML markup?**

If a document is described well (structured and tagged properly), it becomes easy to then transform it into other document types, to include directions for display and styling, and to perform computational analysis. 

Those attending the workshop may already be familiar with this. The section below provides a very brief intro to XML for those who are unfamiliar with it so that you can follow along with the Oxygen XML Editor demo.

## XML by Example

To illustrate XML, TEI By Example provides a fun example of encoding (another word for markup). (Note we will not discuss TEI in this workshop.)

<img width="300" alt="image" src="https://github.com/ubc-library-rc/oxygen/assets/100799888/6a27bddd-9836-40c6-8481-e59de5bb75b1">

Here is an example of a list of items. Let’s assume it’s a shopping list someone made: with a bit of contextual information, a person would be able to understand this as a list of grocery items. We can also interpret each item as separate based on how it’s formatted as separate lines or line breaks.

To encode this to be readable by a computer, you would need to describe not only the content, but also the structure, using elements and tags. An element is a building block of XML, the containers that provide structure to the content, for example, <paragraph>, <name>, and <subject> are elements. Tags denote the start and end of an element in a machine readable format (they signal an element). They are usually enclosed in angle brackets. Tags almost always appear in pairs (opening and closing). For instance:

**Element:** ``<paragraph>Hello!</paragraph>``
**Opening tag:** ``<paragraph>``
**Closing tag:** ``</paragraph>``
  
XML does not tell you _how_ to encode: it is a metalanguage, which is a language used to describe other languages. For example, the words "noun," "verb," "adverb," and "adjective" are used to describe how many languages operate, but are not the language in and of themselves. Similarly with XML, it provides you with a kind of grammar. How to encode (what elements you choose) are up to you and the object you’re encoding. So looking at the example from TEI By Example, there are multiple ways you could go about encoding, depending on your research purpose and how you’re looking at the list.
  
You can encode them as a list of items, for instance:

<img width="482" alt="image" src="https://github.com/ubc-library-rc/oxygen/assets/100799888/c9adbec2-fb5d-410c-a10c-ef414de6910c">

Or even more structurally, as lines of text without focusing on the “items” nature (below “lg” was used by the author to indicate line group).

<img width="458" alt="image" src="https://github.com/ubc-library-rc/oxygen/assets/100799888/bef12b09-d681-4d4b-8d4f-50fbb6ec296b">

Or, as TEI by Example illustrates, could this be a poem, based on the metrical composition and structure and rhyme? If so, you might want to encode it differently to more accurately describe your object. We can see the rhyme in every four lines, so you might do something like:

<img width="443" alt="image" src="https://github.com/ubc-library-rc/oxygen/assets/100799888/7d31542b-a7df-4fb9-9f22-5efd6e075050">

