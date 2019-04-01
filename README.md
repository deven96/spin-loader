# Spin Loader

Simplistic Loader to display when running background processes

## Usage

```python
    import time
    from spinner import spin

    spin_handler = spin(before="Please be patient while i do x")
    # simulate a computation taking 5 seconds
    time.sleep(5)
    spin_handler.terminate()
```

    
