```c

                  #define P(a,b,c) a##b##c
                #include/*++**++*/<curses.h>
              int         c,h,            v,x,y,s,                i,b; int
            main            () {            initscr(              ); P(cb,
          rea,                k)()                ;///
        P(n,                  oec,                ho)(
       )/*     */             ;for            (curs_set(0); s=        x=COLS/2
      ; P(    flu,            shi,          np)()){ timeout(y=c=      v=0);///
      P(c,    lea,            r)()          ;for              (P (
      mva,     d,             dstr        )(2,                3+x,
      G) ;                  ; P(        usl,                  eep,    )(U)){//
       P(m,               vad,         dstr                   )( y    >>8,x,//
    "    "); for(i=LINES; /*           */ i                   -->0
  ; mvinsch(i,0,0>(~c|i-h-H             &h-i                  )?' '
:(i-                      h|h-            i+H)            <0?'|'      :'=' ));
if((                       i=( y            +=v=        getch(        )>0?I:v+
  A)>>8)>=LINES||mvinch(i*=   0<i,            x)!=' '||' '
  !=mvinch(i,3+x))break/*&%   &*/;              mvaddstr(y
    >>8,                   x,0>v                      ?F:B        ); i=--s
    /-W;                  P(m,                        vpr,        intw)(0,
     COLS-9," %u/%u ",(0<i)*                  i,b=b<i?i:
      b); refresh(); if(++                    c==D){ c
                        -=W; h=rand()%(LINES-H-6
                          )+2; } } flash(); }}

```

- What do i do: fullstack web developing, binary analysis, desktop app developing with Qt, DevSecOps.
- What am i learning: Cyberspace Security as an undergraduate major in Xidian University.
- Blog: [Reverier's Blog](https://blog.woooo.tech/)
- Ops website: [XIDIAN CTF Archive](https://ctf.xidian.edu.cn/), [XIDIAN Forensics](https://forensics.xidian.edu.cn/), [XDSEC](https://www.xdsec.org/)

- Organizations: a member of [XDSEC](https://www.xdsec.org/) ([**XDSEC@GitHub**](https://github.com/XDSEC)) / [L-team](https://l.xdsec.org/).

- How to reach me:
  - personal mail: [reverier.xu@outlook.com](mailto:reverier.xu@woooo.tech).
  - org mail: [reverier.xu@xdsec.club](mailto:reverier.xu@xdsec.club).
