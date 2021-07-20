Minimal working example to reproduce error with pytest

If running `pytest` without `pytest.ini`, this will produce an error message:
```
$ pytest
ERROR: /home/fzeiser/met/pytest_error_unexpected_value_continuation/setup.cfg:17: unexpected value continuation
```

If `pytest.ini` is added (remove `.bak` from the file), pytest will work as expected. 
