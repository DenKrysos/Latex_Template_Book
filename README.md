# Latex_Template_Book
A Template together with some Macros and ready-to-use set up suroundings for Use with "LuaLatex"

-> Supports UTF-8, especially Japanese Kanji & Kana Input

- Spoiler-Environment. Can be dynamically clicked, while previewing on a computer, to show or hide the filled in text. (Uses OCG, optional content group)
- Macro to automatically include a "standalone tikz picture" with the best options.
  -> Ensures, that the picture does not exceed the page/environment size on any side
  -> Allows several options, like rotate, crop, insert as plain-text (render together with main file) or as pre-rendered pdf-picture.
  -> If desired the pictures can be included as "buildnew". Means: They are only rendered new, if they changed. Saves a lot of compilation time.
  -> Allows explicit scaling and positioning
- Set up for Biblatex
- Set up for glossaries (requires external builder, pretty easy to configure)
- tikz:
  -> Some 3-Dimensional Graphic Generation done in tikz
  -> Flow Graph Toolset

- For sure some more features I can't quite recall. That thing is huge...
