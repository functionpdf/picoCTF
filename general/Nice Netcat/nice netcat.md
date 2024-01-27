# nice netcat
## artifacts:
`$ nc mercury.picoctf.net 22342`
## process
### step-1
So I obviously need to use netcat for this. They very nicely gave us the command, so I just pasted it in my terminal.
### step-2
We get long string of numbers. The problem description tells us that it does not speak English, so it's obviously some sort of cipher. Let's plug this into Cyberchef.
### step-3
`Magic` tells me that `From Decimal` will give me the flag.
## flag
`picoCTF{g00d_k1tty!_n1c3_k1tty!_5fb5e51d}`
