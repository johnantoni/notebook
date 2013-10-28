## CUT/COPY/PASTE

Ever try to cut (or copy) some lines and paste to another place? If you need to count the lines first, then try these to eliminate counting task.
Cut and paste:

* Position the cursor where you want to begin cutting.
* Press v (or upper case V if you want to cut whole lines).
* Move the cursor to the end of what you want to cut.
* Press d.
* Move to where you would like to paste.
* Press p to paste after the cursor, or P to paste before.
* Copy and paste can be performed with the same steps, only pressing y instead of d in step 4.
* The name of the mark used is related to the operation (d:delete or y:yank).

I found that those mark names requires minimal movement of my finger.

## UNDO

press 'u' to undo

## Extras

Press f5 to clear the ctrl-p cache, vendor/bundle is excluded by default

Once the buffergator navigator is open you can close a buffer by using the arrow keys to navigate to it and hitting 'x' to close it

# custom color settings

    " highlight the status line
    hi StatusLine ctermfg=blue ctermbg=yellow

    " Set gutter background to black
    hi SignColumn ctermbg=white

    " make the omnicomplete text readable
    hi Pmenu ctermbg=238 gui=bold

    " autocomplete
    hi Search ctermbg=156 ctermfg=16

    " vertical line color
    hi CursorColumn ctermbg=16

    " horizontal line color
    hi CursorLine cterm=NONE ctermbg=white
