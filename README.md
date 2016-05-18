# Opengl-Functions-and-Enumerants
Excel files which lists the Opengl functions and enumerants (through version 3.3)

This excel file consists of two main tabs which list all known, standard functions and enumerants for Opengl through version 3.3.  Most of the standard documentation does not let programmers know which functions and values are supported in various versions of Opengl, which are deprecated and which are considered "core profile".  For me this was necessary since many of the machine upon which I work and write code, do not support the Opengl state-of-the-art graphics. Often I am limited to versions less than 4.0.  This excel file is my attempt to clear up some of the lack of clarity and enable me to properly target my code to supported functionality when working with legacy versions of Opengl.

The enumerants are organized alphabetically by the Opengl version in which they were introduced. The enumerant name and values are given. The columns in the center of the sheet will show which enumerants are considered core profile, designated with a "P" and in which version they may have been deprecated, desinated with a "D" (nearly all non-core values were deprecated in version 3.1). It is useful to know which of these values are deprecated since no standard documentation seems to show it.  Finally, the columns on the right show which Opengl extensions defined the values.  These are listed by index number and name as defined in the Opengl Registry (https://www.opengl.org/registry/).

The functions sheet has a similar organization as the enumerants sheets described above. Functions are listed alphabetically by vthe version in which they became part of the Opengl standard.  The columns in the center show which functions are considered core, designated by "P" and which were deprecated, designated by "D".  A "D" in the "GL 3.1" column, denotes the function whas deprecated in Opengl version 3.1.  On the right-side of the sheet the extension registry indices and names are listed (if applicable) and the full function prototype is given, if the function has been defined in an extension.  With this information, it is easy to determine which extensions must be supported in order to utilize a particular function. It is also possible to use the prototype to create a suitable typedef for describing the function if desired.

If you stumble across this file, I hope you find it is useful.

Suggested updates, corrections, or additions are welcome.  I hope provide an expanded version soon which includes the Opengl version 4.0 - 4.+ definitions.

Best regards,
Jim Kellams

