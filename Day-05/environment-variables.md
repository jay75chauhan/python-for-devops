# Environment variables are accessed through os.environ:

```
import os
print(os.environ['HOME'])
```

# To see a list of all environment variables:

```
import os
print(os.environ)
```

```
import os
# Returns `None` if the key doesn't exist
print(os.environ.get('KEY_THAT_MIGHT_EXIST'))

# Returns `default_value` if the key doesn't exist
print(os.environ.get('KEY_THAT_MIGHT_EXIST', default_value))

# Returns `default_value` if the key doesn't exist
print(os.getenv('KEY_THAT_MIGHT_EXIST', default_value))
```
