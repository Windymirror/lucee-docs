### Non-Member Function

```luceescript+trycf
animals = {
	cow: "moo",
	pig: "oink"
};

// Show current animals
Dump(
	label: "Current animals",
	var: animals
);

// Clear struct
structClear(animals);

// Show animals, now empty
Dump(
	label: "Animals after calling StructClear()",
	var: animals
);
```