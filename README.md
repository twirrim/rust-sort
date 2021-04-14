# rust-sort

sort algorithms

## exchange sorts

### bubble sort

```rust
extern crate sort;

use sort::bubble_sort;

fn main() {
    let mut data = vec![5, 4, 3, 2, 1];
    bubble_sort(&mut data);
    assert_eq!(data, [1, 2, 3, 4, 5]);
}
```

## selection sorts

### selection sort

```rust
extern crate sort;

use sort::selection_sort;

fn main() {
    let mut data = vec![5, 4, 3, 2, 1];
    selection_sort(&mut data);
    assert_eq!(data, [1, 2, 3, 4, 5]);
}
```

## insertion sorts

### insertion sort

```rust
extern crate sort;

use sort::insertion_sort;

fn main() {
    let mut data = vec![5, 4, 3, 2, 1];
    insertion_sort(&mut data);
    assert_eq!(data, [1, 2, 3, 4, 5]);
}
```