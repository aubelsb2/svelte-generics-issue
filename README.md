This is for a coule of idea issues:

# Issue 1: `$$Generic` isn't supported

![img_1.png](img_1.png)

It should be used to set the type on the slot here:

![img_3.png](img_3.png)

I expect it to be `string`

# Issue 2: `$$Slots`

![img.png](img.png)

This seems partially supported, since I have a matching 
slot definition below this should be considered in use.

Nor does it offer suggestions:

![img_5.png](img_5.png)

![img_6.png](img_6.png)

# Issue 3: Default import paths

Default import path on a brand new project generated using the "getting started guide" is "wrong".
JetBrains even knows it's wrong:

![img_2.png](img_2.png)

Should be: (relative)

```
    import Table from "./Table.svelte";
```

Given there are no path alias defined.

![img_4.png](img_4.png)

Possibly adjacent to issues like:
* https://youtrack.jetbrains.com/issue/WEB-56970/Sveltekit-path-mappings-from-tsconfig.json-not-used-when-importing-modules

