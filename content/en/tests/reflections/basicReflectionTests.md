---
layout: unittest
tags:
- '#basicReflectionTests'
- serial
- cavity
title: Unit tests for reflections - basicReflection
---

{{< alert title="Note:" >}}
The unit tests pages are automatically generated from the test reports. Some important points to mention:
- The random number generator is seeded with the same seed for parallel/serial runs for the same test case.
- Number of passing tests is the "effective" one (including the ones that fail but are expected to fail)".
- Number of failing tests is the "effective" one (only the ones that fail and are not expected to fail)".
{{< /alert >}}

## Serial unit tests for `basicReflection` in `reflections` library on `[cavity]` case

Tests were performed using [Catch2](https://github.com/catchorg/Catch2) version `3.6.0` (rng-seed: `3975461408`) with the following filters: `[serial] [cavity] [#basicReflectionTests]`.

<i class="fa-sharp fa-solid fa-check -text-primary"></i> <span class="-text-primary">5 Passing</span> test cases  (<span class="-text-primary">20</span> expressions), <i class="fa-sharp fa-solid fa-circle-exclamation -text-warning"></i> <span class="-text-warning">0 Failing</span> test cases  (<span class="-text-warning">0</span> expressions).

### Unconfigured refletion supports basic reflectable OpenFOAM classes both in constructive and documentation modes

Defined in [basicReflectionTests.C#19](https://github.com/FoamScience/openfoam-reflections/blob/wrap/tests/reflections/basicReflectionTests.C#L19)

With expressions:


---

<i class='fa-sharp fa-solid fa-check -text-primary'></i> From file [basicReflectionTests.C#31](https://github.com/FoamScience/openfoam-reflections/blob/wrap/tests/reflections/basicReflectionTests.C#L31).
Belonging to the test section scoped as:

```
Unconfigured refletion supports basic reflectable OpenFOAM classes both in constructive and documentation modes
compiler defaults are reported for non constexpr default-constructible types
```


---

<i class='fa-sharp fa-solid fa-check -text-primary'></i> From file [basicReflectionTests.C#32](https://github.com/FoamScience/openfoam-reflections/blob/wrap/tests/reflections/basicReflectionTests.C#L32).
Belonging to the test section scoped as:

```
Unconfigured refletion supports basic reflectable OpenFOAM classes both in constructive and documentation modes
compiler defaults are reported for non constexpr default-constructible types
```


---

<i class='fa-sharp fa-solid fa-check -text-primary'></i> From file [basicReflectionTests.C#36](https://github.com/FoamScience/openfoam-reflections/blob/wrap/tests/reflections/basicReflectionTests.C#L36).
Belonging to the test section scoped as:

```
Unconfigured refletion supports basic reflectable OpenFOAM classes both in constructive and documentation modes
empty values are reported for non constexpr non default-constructible types
```


---

<i class='fa-sharp fa-solid fa-check -text-primary'></i> From file [basicReflectionTests.C#41](https://github.com/FoamScience/openfoam-reflections/blob/wrap/tests/reflections/basicReflectionTests.C#L41).
Belonging to the test section scoped as:

```
Unconfigured refletion supports basic reflectable OpenFOAM classes both in constructive and documentation modes
onDemand tag and defaults underlying type are reported for pointer types
```


---

<i class='fa-sharp fa-solid fa-check -text-primary'></i> From file [basicReflectionTests.C#43](https://github.com/FoamScience/openfoam-reflections/blob/wrap/tests/reflections/basicReflectionTests.C#L43).
Belonging to the test section scoped as:

```
Unconfigured refletion supports basic reflectable OpenFOAM classes both in constructive and documentation modes
onDemand tag and defaults underlying type are reported for pointer types
```


---

<i class='fa-sharp fa-solid fa-check -text-primary'></i> From file [basicReflectionTests.C#50](https://github.com/FoamScience/openfoam-reflections/blob/wrap/tests/reflections/basicReflectionTests.C#L50).
Belonging to the test section scoped as:

```
Unconfigured refletion supports basic reflectable OpenFOAM classes both in constructive and documentation modes
RTS options are reported for a base model class
```


---

<i class='fa-sharp fa-solid fa-check -text-primary'></i> From file [basicReflectionTests.C#51](https://github.com/FoamScience/openfoam-reflections/blob/wrap/tests/reflections/basicReflectionTests.C#L51).
Belonging to the test section scoped as:

```
Unconfigured refletion supports basic reflectable OpenFOAM classes both in constructive and documentation modes
RTS options are reported for a base model class
```


---

<i class='fa-sharp fa-solid fa-check -text-primary'></i> From file [basicReflectionTests.C#53](https://github.com/FoamScience/openfoam-reflections/blob/wrap/tests/reflections/basicReflectionTests.C#L53).
Belonging to the test section scoped as:

```
Unconfigured refletion supports basic reflectable OpenFOAM classes both in constructive and documentation modes
RTS options are reported for a base model class
```


---

<i class='fa-sharp fa-solid fa-check -text-primary'></i> From file [basicReflectionTests.C#54](https://github.com/FoamScience/openfoam-reflections/blob/wrap/tests/reflections/basicReflectionTests.C#L54).
Belonging to the test section scoped as:

```
Unconfigured refletion supports basic reflectable OpenFOAM classes both in constructive and documentation modes
RTS options are reported for a base model class
```

### Configured refletion supports basic reflectable abstract RTS OpenFOAM classes both in documentation mode

Defined in [basicReflectionTests.C#60](https://github.com/FoamScience/openfoam-reflections/blob/wrap/tests/reflections/basicReflectionTests.C#L60)

With expressions:


---

<i class='fa-sharp fa-solid fa-check -text-primary'></i> From file [basicReflectionTests.C#71](https://github.com/FoamScience/openfoam-reflections/blob/wrap/tests/reflections/basicReflectionTests.C#L71).
Belonging to the test section scoped as:

```
Configured refletion supports basic reflectable abstract RTS OpenFOAM classes both in documentation mode
child models report their concrete type as value in selection keyword
```


---

<i class='fa-sharp fa-solid fa-check -text-primary'></i> From file [basicReflectionTests.C#81](https://github.com/FoamScience/openfoam-reflections/blob/wrap/tests/reflections/basicReflectionTests.C#L81).
Belonging to the test section scoped as:

```
Configured refletion supports basic reflectable abstract RTS OpenFOAM classes both in documentation mode
child models report reflected members of their base alongside their own
```


---

<i class='fa-sharp fa-solid fa-check -text-primary'></i> From file [basicReflectionTests.C#82](https://github.com/FoamScience/openfoam-reflections/blob/wrap/tests/reflections/basicReflectionTests.C#L82).
Belonging to the test section scoped as:

```
Configured refletion supports basic reflectable abstract RTS OpenFOAM classes both in documentation mode
child models report reflected members of their base alongside their own
```

### Configured refletion supports basic reflectable concrete RTS OpenFOAM classes both in documentation mode - false

Defined in [basicReflectionTests.C#86](https://github.com/FoamScience/openfoam-reflections/blob/wrap/tests/reflections/basicReflectionTests.C#L86)

With expressions:


---

<i class='fa-sharp fa-solid fa-check -text-primary'></i> From file [basicReflectionTests.C#98](https://github.com/FoamScience/openfoam-reflections/blob/wrap/tests/reflections/basicReflectionTests.C#L98).
Belonging to the test section scoped as:

```
Configured refletion supports basic reflectable concrete RTS OpenFOAM classes both in documentation mode - false
```


---

<i class='fa-sharp fa-solid fa-check -text-primary'></i> From file [basicReflectionTests.C#104](https://github.com/FoamScience/openfoam-reflections/blob/wrap/tests/reflections/basicReflectionTests.C#L104).
Belonging to the test section scoped as:

```
Configured refletion supports basic reflectable concrete RTS OpenFOAM classes both in documentation mode - false
```

### Configured refletion supports basic reflectable concrete RTS OpenFOAM classes both in documentation mode - true

Defined in [basicReflectionTests.C#86](https://github.com/FoamScience/openfoam-reflections/blob/wrap/tests/reflections/basicReflectionTests.C#L86)

With expressions:


---

<i class='fa-sharp fa-solid fa-check -text-primary'></i> From file [basicReflectionTests.C#98](https://github.com/FoamScience/openfoam-reflections/blob/wrap/tests/reflections/basicReflectionTests.C#L98).
Belonging to the test section scoped as:

```
Configured refletion supports basic reflectable concrete RTS OpenFOAM classes both in documentation mode - true
```


---

<i class='fa-sharp fa-solid fa-check -text-primary'></i> From file [basicReflectionTests.C#104](https://github.com/FoamScience/openfoam-reflections/blob/wrap/tests/reflections/basicReflectionTests.C#L104).
Belonging to the test section scoped as:

```
Configured refletion supports basic reflectable concrete RTS OpenFOAM classes both in documentation mode - true
```

### Unconfigured reflection system is able to build concrete objects without explicit headers inclusion

Defined in [basicReflectionTests.C#107](https://github.com/FoamScience/openfoam-reflections/blob/wrap/tests/reflections/basicReflectionTests.C#L107)

With expressions:


---

<i class='fa-sharp fa-solid fa-check -text-primary'></i> From file [basicReflectionTests.C#124](https://github.com/FoamScience/openfoam-reflections/blob/wrap/tests/reflections/basicReflectionTests.C#L124).
Belonging to the test section scoped as:

```
Unconfigured reflection system is able to build concrete objects without explicit headers inclusion
typeName matches the concrete type
```


---

<i class='fa-sharp fa-solid fa-check -text-primary'></i> From file [basicReflectionTests.C#133](https://github.com/FoamScience/openfoam-reflections/blob/wrap/tests/reflections/basicReflectionTests.C#L133).
Belonging to the test section scoped as:

```
Unconfigured reflection system is able to build concrete objects without explicit headers inclusion
default-constructed members do not match values in skeleton
```


---

<i class='fa-sharp fa-solid fa-check -text-primary'></i> From file [basicReflectionTests.C#124](https://github.com/FoamScience/openfoam-reflections/blob/wrap/tests/reflections/basicReflectionTests.C#L124).
Belonging to the test section scoped as:

```
Unconfigured reflection system is able to build concrete objects without explicit headers inclusion
typeName matches the concrete type
```


---

<i class='fa-sharp fa-solid fa-check -text-primary'></i> From file [basicReflectionTests.C#133](https://github.com/FoamScience/openfoam-reflections/blob/wrap/tests/reflections/basicReflectionTests.C#L133).
Belonging to the test section scoped as:

```
Unconfigured reflection system is able to build concrete objects without explicit headers inclusion
default-constructed members do not match values in skeleton
```