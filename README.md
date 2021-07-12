# shell tutorial

## Math Operator
https://bash.cyberciti.biz/guide/Perform_arithmetic_operations

```sh
echo $((20+5))
echo $((20-5))
echo $((20/5))
echo $((20*5))
echo $((20%5))
echo $((20**5))

```



## sed
sed - stream editor
removing first word
```sh
sed 's/\w*.//' [file name]
```
test auto6