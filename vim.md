# Comandos do Vim

1.  delete between characters di 'character'
    {
    delete este conteudo com di{}
    }

2.  delete the next 3 word d3w
    palavra palavra palavra sobrou

3.  copiar e colar: entre no modo visual selecione o conteúdo e delete,
    o que foi recem deletado fica guardado no cache e pode ser colado com p

    corte: {
    corte
    este
    conteúdo
    }
    cole aqui:

4.  change inside the parenthesis ci(modifique o texto aqui)

5.  change the whole line cc or S

6.  exit vim :q,
    exit vim without save :q!,
    exit writting and quitting :wq

7.  pressing i insert before the cursor:

8.  pressing a insert in at the back of the cursor:

9.  pressing o insert a new line below the cursor, 
    pressing O insert a new line above the cursor

10. A append at the end of the line

11. I insert at the beggining of the line

12. :set number show line numbers

13. 10j moves the line below 10 times,
    10k moves the line up 10 times

14. :set relativenumber show relative lines numbers

15. pressing u in normal-mode undo the last editing, 3u undo 3 times

16. pressing CTRL+R redo the last editing, 3CTRL+R redo 3 times

17. in visual mode press y (yank/yield) to copy, 
    yy copy the full line,
    Y also copy the full line ?,
    yiw copy the word around the cursor,

18. p pastes the copy content after the cursor,
    P pastes before the cursor 

19. c changes the line entering in insert mode,
    cc changes the line without delete the line and also entering in insert mode,
    C changes the rest of the line,
    ciw change inner word replace the word around the cursor,
    ci" change inner quotations mark change a string

20. d delete,
    dd delete the line,
    D delete the rest of the line,
    dw delete a word from cursor forward,
    db delete a word from cursor backward,
    diw delete inner word from cursor, 
    d0 delete from the cursor to the begining of the line,
    d$ delete from the cursor to the end of the line (same as upper case D)

21. in normal mode press R and a letter to replace a character

22. in normal mode use w to jump to the next word.
    upper case W only consider spaces as word breaker 

23. in normal mode use b to jump back a word.
    upper case B only consider spaces as word breaker

24. e jumps to the end off a word

25. zero jumps to the beginning of a line in the normal mode

26. $ jumps to the end of a line in normal mode

27. % jumps to the closing character ({[""]}),
    can be combine with delete and etc...

28. t* jumps to before the next * character,
    upper case T do the same thing backwards,
    dt* deletes everything befote the next * character

29. f* jumps to the next * character,
    upper case F do the same thing backwards

30. gg same as Home key,
    G same as End key,
    93G goes to line number 93,
    gj move cursor down, same as page down

31. >> indent the line, same as Tab

32. . (dot) will repeat the last command you've executed
