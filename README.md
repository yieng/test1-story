# FirstDrafter
*A pair of tools enabling novelists to write their first draft the way it's meant to be written:*  
*without abandon, without editing, and without looking back*

There are two versions of this app, each for a different purpose:
- `writer-helper.sh`: for writers who begin with a premise or an opening scene, and
- `start-at-the-end.sh`: for writers who begin with the ending.

They work in similar ways. For simplicity, both are called FirstDrafter.

More details to come soon.

### Update, 12 December 2019:
Added a Python script `firstDrafter.py` which does the same thing as `writer-helper.sh`.
**The best part about this?** This works on Python 3.x on both Windows and Mac; there are no fancy steps to take! Just type `python firstDrafter.py` (or `py -3 firstDrafter.py` if you have Python 2.x and 3.x on your machine)

## Features:
- To run the script:
  - In the Mac Terminal, use the command ```chmod +x [name of .sh script]; ./[name of .sh script]```.
  - In the [Hyper](https://hyper.is) terminal, use the command ```bash [name of .sh script]```.
- This tool discourages you from editing too early:
  - When you run FirstDrafter on Mac or [Hyper](https://hyper.is) Terminal and you use the arrow keys, you get weird outputs (a combination of the A, B, C, D keys and symbols), and that is enough to discourage you from looking back and editing your previous written work.
- Press `Enter` / `Return` to save what you typed.
- Word count is automatically computed as you save your work.
- Use `Ctrl+C` (Windows) / `Control+C` (Mac) to exit FirstDrafter. (Don't forget to save your work!)

## Known issues:
- ### Please don't use double or triple asterisks because they will mess up your first draft.
   If your input content includes a series of asterisks, say \*\* or \*\*\* or more, a horrible thing happens: instead of what you type, all the files in the same directory as writing-helper.sh will be inputted to your work-in-progress. So, just in case your work contains sensitive content, please refrain from using asterisks. Otherwise, you will be puzzled at the appearance of strange file names in your draft.
- Each time the prompt only admits 1024 characters, including the new line character. You cannot hit **Enter** to save your work unless you have typed 1023 or fewer characters.
