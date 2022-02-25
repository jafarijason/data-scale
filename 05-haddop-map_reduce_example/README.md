# Use the Streaming Interface

## map step
```
echo "foo foo quux labs foo bar quux" | ./mapper.py
```

## shuffle step
```
echo "foo foo quux labs foo bar quux" | ./mapper.py | sort -k1,1
```

## reducer step
```
echo "foo foo quux labs foo bar quux" | ./mapper.py | sort -k1,1 | ./reducer.py
```
