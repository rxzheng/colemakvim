This is a tutorial on how to rebind vim with Colemak bindings, replacing hjkl to hnei

Other keyboard layouts also work, just replace hnei with your corresponding layout.

```bash
vim ~/.vimrc
```
Copy paste this into the vimrc file.
```bash
noremap j n
noremap e k
noremap i l
#noremap h h
```
Type 
```bash
:wq
```

Already done! No plugin managers, just a great minimalist approach.

However, I use some  extra keybinds to give back some functionality:
Here are the binds that I use:
```bash
noremap n j
noremap e k
noremap i l
noremap u i
noremap l u
```