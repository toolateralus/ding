### Built with the Ela compiler 
[A link to the compiler](https://github.com/toolateralus/ela)

The build binary is for linux, built on arch. It has no dependencies, so it should work everywhere.
The compiler is not available on windows.

### usage: 
`./ding <n_minutes:float>`

> Note: this uses seconds-precision. Not sure why you'd need less for a terminal based visual counter, but still worth noting.

### examples 
- Run for 30 seconds.
`./ding .5`

- Run for 90 minutes.
`./ding 90`
