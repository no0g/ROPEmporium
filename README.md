# Attempting ROPEmporium

 - ROPEmporium is a place to "Learn return-oriented programming through a series of challenges."
 - They have 8 challenges 
 - Current progress of mine ***8/8*** 
 - Will post writeup on [my site](https://jmp2rsp.tech) soon!


1. ret2win
>Locate a method that you want to call within the binary.
>Call it by overwriting a saved return address on the stack.

2. split
>The elements that allowed you to complete ret2win are still present, they've just been split apart.
>Find them and recombine them using a short ROP chain.

3. callme
>Reliably make consecutive calls to imported functions.
>Use some new techniques and learn about the Procedure Linkage Table.

4. write4
>Our first foray into proper gadget use.
>A useful function is still present, but we'll need to write a string into memory somehow.

5. badchars
> An arbitrary write challenge with a twist; certain input characters get mangled as they make their way onto the stack.
> Find a way to deal with this and craft your exploit.

6. fluff
> The concept here is similar to the write4 challenge,
> although we may struggle to find simple gadgets that will get the job done.

7. pivot
> There's only enough space for a small ROP chain on the stack,
> but you've been given space to stash a much larger chain elsewhere.
> Learn how to pivot the stack onto a new location.

8. ret2csu
> We're back in ret2win territory, but this time with no useful gadgets.
> How will we populate critical registers without them?
