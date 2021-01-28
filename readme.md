in gnl main c files.
there's a line like " if (**str) " at rtn() function. (before free())
it causes memory leaks when invalid fd comes in.
so, need to remove that line.
already did.
