# !TapirMail - 1.09 (05 Jan 2013)

A simple email client for RISC OS.

See http://www.flypig.co.uk/tapirmail for more info

## Building

For a successful build, you'll need to ensure the following have been seen by
the filer:

1. !gcc 3.4.4 (or possibly later)
2. !OSLib 6.50 (or possibly later)
3. !StubsG 0.04 (or possibly later)

Open a task window and execute the BuildAll script:

```
Obey BuildAll
```

If everything goes to plan, this will build the TapirMail binary and install
it as !TapirMail.!RunImage .

The BuildAll obey script just calls the other build scripts in order, and you
can call them individually if you prefer.

To clean out all the build artefacts (including the final executable) you can
use:

```
Obey BuildClean
```

## Licence

TapirMail is open source, released under an MIT licence. See the LICENCE
file.

## Contact

- David Llewellyn-Jones
- david@flypig.co.uk
- http://www.flypig.co.uk
