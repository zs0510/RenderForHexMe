# RenderForHexMe
A render based on [polyscope](https://github.com/nmwsharp/polyscope) for models of [HexMe](https://www.algohex.eu/publications/hex-me-if-you-can/).

Compilation Environment: **macOS** 13.2.1

#### Usage:

```shell
Usage: /bin/RenderForHexMe input0 [input1] [input2] [...]

	--input0 TEXT REQUIRED     Input tet mesh INPUT in .vtk format. (string, required)
	--input1 & ... TEXT        Input tet mesh INPUT in .vtk format.
```



For example:

```shell
$ /bin/RenderForHexMe /models/i01u_m1.vtk
```

![example](https://github.com/zs0510/RenderForHexMe/blob/main/image/i01u_m1.png)



For another example:

```shell
$ /bin/RenderForHexMe /models/n01c_cross_cyls_sr.vtk /models/s01u_cube.vtk
```

![example](https://github.com/zs0510/RenderForHexMe/blob/main/image/n01u_and_s01u.png)
