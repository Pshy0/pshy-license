# TFCL License (True Free CopyLeft License)

A simple free copyleft license, based on the MIT License.



## Status

This TFCL License is currently a work in progress.
This is the changes I intent to make:
 - Adapt the license's terms to fit all kind of materials (rather than just softwares).
 - Simplify the license terms, to make it concise and easy to understand.
 - Make it clear the words I use have no externally-defined legal meaning.



## Intents

This describes the intents of this license. Future versions may be adapted to better fit them.
 - Grant the rights commonly granted by free licenses.
 - Grant the right to integrate any change, made to licensed materials, under TFCL.
 - Grant the right to format the copyright notice as wished (helps integration).
 - Grant the right to reference the license and not include it (helps integration).
 - Do not spread the license to works integrating a TFCL component.



## Reasons and Purpose

Most copyleft licenses pretend to be free. However, many prohibits the use of the licensed materials in some situations. This includes the following scenarios:
 - You cannot release sources (due to company policy, legal, or safety reasons).
 - When you want to use a different license for your project.
 - When you want to use components that have two different spreading licenses.

The GNU GPL is a perfect example of such a fake-free license. For sure, it guarantees that the program stays open-source, but the additional restrictions about where, and, how you can use the licensed material, violates the principles of a free software.
The goal of the GPL is not to encourage freedom. It is to give itself a monopole, by spreading like an infection. If you took the terms of the GPL to build your own license, it would not even be compatible with the GPL. That is a huge problem to me.

The MIT license, in the other hand is too permissive. It allows the licensed work to be re-licensed, in a way that would make it non-free. I am not against my work being re-used, even in private projects, with proprietary licenses. But I find immoral that my work be re-used in a project that pretends to be free as well, while in reality, it, or a modified version of it, is re-licensed in a way that prevent, even myself, from re-using it the way I originally intended everyone to be able to.

This fixes this issue in a very simple way: By requiring that all modifications to the original work are also released under the original license.

But are you not allowed to sub-license the original work? The original, and all modifications, will abide by the TFCL, but you are allowed to add a TFCL component to a non-TFCL project. Let's say you create a project with only one component (the TFCL one), then you can release the project, as a whole, with a different license.

In addition, I wanted to make crediting easier. Instead of having to include this whole license into your project, you can use a reference to it. And you do not have to strictly respect the copyright notice format, as long as the information it contains remains.

It also requires modified versions to be identified as such (That is just so bad modifications are not attributed to the original author).



## The License

The license reads as follow:
```
TFCL License (https://github.com/Pshy0/pshy-license)

Copyright (c) [<publication date>] [<holder>] [<contact>] [<original repo>]

This license applies to the licensed material, without intent to enforce any
licensing to a project implementing it as a component.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software, to deal in the software without restriction, including the
rights to use, copy, modify, merge, publish, distribute, sublicense, and/or
sell copies of the software, subject to the following conditions:

- The copyright notice information, and a reference to this license, shall be
included in all copies or substantial portions of the software.

- Modified versions must be identified as such.

- If the sources of a sublicensed version of the software are released under
a different license, then the changes are also released with the original
license alone. If the changes are not submitted to the original software,
then they are also released into public domain.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

**NOTES:**
- The copyright notice is the second paragraph.
- The copyright notice does not have any specific format, but it is a good idea to include a contact information or a link to your original work.
- I recommend keeping the `Copyright` word and all the copyright notice's fields on the same line, so it is clearer what constitutes the copyright notice. Or you can indent the whole paragraph to make it clearer.



## Trivia

- I named the license `True Free CopyLeft` because it grants the rights a free license should grant, while mocking the copyleft licenses that does not.
