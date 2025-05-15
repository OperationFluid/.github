# Operation Fluid

Fluid is a modern operating system currently in development. Nowadays,
a lot of operating systems are slow because of suboptimal abstractions
that should be implemented in the  userland to only use resources when
actually being used.

More functionality in  the kernel might come with  convenience for the
developers, but due to the inevitable existence of bugs in every large
codebase, less functionality in the kernel has the benefits of:

- **Security & Privacy**  
    If an operating  system contains less  code, more  people consider
    reading through it, partially  or completely. That results in more
    bugs being found and fixed before  before a bad actor has a chance
    of using it for malicious purposes.

- **Stability**  
    Malfunctioning  code in a  kernel has  caused partial or  complete
    crashes which wouldn't have happened if there was less code in the
    kernel. If a bad behavior happens isolated in the userspace, those
    problems cause much less harm.

## Used Technologies

We use few foreign technologies; most software used in Operation Fluid
is written by the members to better fit our use case.

The following is an (incomplete) list of technologies we use:

- Zig (programming language)
- Bash (shell language; used for utility scripts)
- Python (script language; used for cross-platform utility scripts)
- Limine (bootloader)

There are some technologies that  weren't mentioned as they are almost
implied in OS development.

## Contributing

At the moment, the project is closed-source. That is due to tendencies
in the developer community to express their discontent  with a project
in an overly harsh way even though the project was only released as an
Alpha. Such  behavior doesn't  solve problems  and much  rather causes
more, thus it was prevented.

For expressing interest in helping with this new project, please write
a message [via E-Mail](mailto:fluid@jarsocial.com), preferably stating
your interest in contributing to Operation Fluid in the subject line.
