# :cat: scratchblocks-node

[Scratchblocks](https://github.com/scratchblocks/scratchblocks) alternative. There's no code here yet.

On the scratch forums and in the wiki, scratchblock code is written in a given natural language, which is transformed into svg Scratch blocks using javascript.
We'd like to avoid client-side javascript and enable svg rendering on the server.

Improved features would be to: 

* highlight blocks (not just lines), by grayscaling the rest (easy)
* animate the addition or removal of blocks with css (hard)
* could it not be a plugin for prism.js? (ridiculous)

Finally, using this in a deno/fresh project would speed up the scratch tutorial presentation. In stead of a another javascript in the client like reveal.js, a similar presentation could be rendered on the server ahead of time.
