#programming/c

[wikipedia ](https://en.wikipedia.org/wiki/Data_structure_alignment)

[Differences between `sizeof` and `alignof`](https://stackoverflow.com/a/11386991)

Data structures are stored as a integrated block in CPU. Each structure are aligned to be approached efficiently and being able to contain all of its members. For a single type, `sizeof` and `alignof` wold return the same value. But for complex data structures, `sizeof` returns the summary of the size of its members' type, while `alignof` returns the overall alignment of the structure.