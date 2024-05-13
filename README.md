
<p align="left">
  <img src="https://komarev.com/ghpvc/?username=v4ms&label=Profile%20views&color=f5c2ec&style=flat" alt="v4ms" />
</p>


```assembly
section .data
    message db 'on foenem', 0

section .text
    global _start

_start:
    mov eax, 4
    mov ebx, 1
    mov ecx, message
    mov edx, 9
    int 0x80

    mov eax, 1
    xor ebx, ebx
    int 0x80
```
