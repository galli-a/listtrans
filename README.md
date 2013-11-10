# `listtrans`

Copy of the `listtrans.vim` plugin by Damian Conway, to toggle between a comma separated list of words and a bulleted list

## Usage

The plugin makes available a function that toggles between a comma separated list of items and a bulleted list. It is smart enough to detect and retain the most common conjunctions, for the English language.

Mapping examples:

	nmap <leader>l :call ListTrans_toggle_format()<CR>
	vmap <leader>l :call ListTrans_toggle_format('visual')<CR>
