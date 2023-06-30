---
layout: default
title: Lesson 2 - LaTeX Environments
nav_order: 1
parent: Lessons
---

{: .no_toc}
# Lesson 2 - LaTeX Environments

In this lesson, we will take a look at some of the environments LaTeX has to offer, including bulleted and numbered lists, figures, and equations.

<details markdown="block">
  <summary>
    Table of Contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

## Lesson Objectives

- objectives 

<!-- ## Lesson Video

The following video demonstrates each of the steps outlined below in text.
<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/a347ed63-745d-4d08-8b9a-98b2dd0d0e14/public?autoplay=false&automute=false"></iframe>
[View original here.](https://echo360.ca/media/a347ed63-745d-4d08-8b9a-98b2dd0d0e14/public) -->

## What's an Environment?

An environment is a special section of your LaTeX document that's formatted differently than the rest of your document. In the previous lesson, we went over inline math expressions which are also considered environments.

Usually, environments begin with a `\begin{environment name}` and end with a `\end{environment name}`. 

LaTeX offers many environments, but here we will cover lists, figures, and equations.

## Lists

We have two different types of lists to cover, bulleted lists and numbered lists.

### Bulleted Lists

- To create a bulleted list, we must create an `itemize` environment. This means we must start with `\begin{itemize}` and end with `\end{itemize}`.
- Inside our environment, each item of our list will start with `\item` followed by the item itself. Take a look at the example below.

<details markdown="1">
<summary>Bulleted List Example</summary>

{: .label }
Input
```latex
% extra lines of code not shown to save space

\section {Environments}

\begin{itemize}
  \item Rocks
  \item Trees
  \item Lakes
\end{itemize}

\end{document}
```

{: .label .label-green }
Output
<img width="100%" src="../assets/img/lessons/environment1.png">

</details>

### Numbered Lists

- To create a numbered list, we must create an `enumerate` environment.
- Just like the itemize environment, each item of our list will start with `\item` followed by the item itself.

<details markdown="1">
<summary>Numbered List Example</summary>

{: .label }
Input
```latex
% extra lines of code not shown to save space

\section {Environments}

\begin{itemize}
  \item Rocks
  \item Trees
  \item Lakes
\end{itemize}

\begin{enumerate}
  \item One
  \item Two
  \item Three
\end{enumerate}

\end{document}
```

{: .label .label-green }
Output
<img width="100%" src="../assets/img/lessons/environment2.png">

</details>

## Key Points / Summary

- key points