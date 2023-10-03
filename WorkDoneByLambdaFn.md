```python
def calculate_work(initial_ke, final_ke):
    return final_ke - initial_ke
```


```python
def calculate_and_print_work(initial_ke, final_ke, work_function):
    work_done = work_function(initial_ke, final_ke)
    print(f"Work done: {work_done} Joules")

# Example usage with a lambda function
initial_ke = 50  # Initial Kinetic Energy in Joules
final_ke = 120  # Final Kinetic Energy in Joules

# Using a lambda function to calculate work done
work_function = lambda initial_ke, final_ke: final_ke - initial_ke

calculate_and_print_work(initial_ke, final_ke, work_function)
```

    Work done: 70 Joules



```python

```
