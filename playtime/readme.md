np.linspace() creates an array of evenly spaced numbers between a start and end value.

# Why Sine Uses `sin(2πft)`

A sine wave is used for a simple sound because it produces a smooth repeating waveform.

### Formula

```python
audio = np.sin(2 * np.pi * frequency * t)
```

Mathematically:

```text
y = sin(2πft)
```

Where:

* `t` = time
* `f` = frequency in Hz
* `2π` = one complete cycle in radians

### Why `2πft`?

One complete sine cycle goes from `0` to `2π` radians.

If `f = 440 Hz`, the wave must complete **440 cycles per second**.

```text
frequency × time = number of cycles
number of cycles × 2π = radians
```

Therefore:

```text
angle = 2π × f × t
```

Then:

```text
sin(angle)
```

produces the waveform amplitude.

### In short

```text
sin(2πft)
   ↓
2π → one complete cycle
f  → cycles per second
t  → time
   ↓
sine-wave amplitude
```
