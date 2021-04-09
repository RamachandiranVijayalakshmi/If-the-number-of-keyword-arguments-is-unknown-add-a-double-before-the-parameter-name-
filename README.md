## If-the-number-of-keyword-arguments-is-unknown-add-a-double-before-the-parameter-name-
## Sample code to check the details 
```sh
def my_function(**kid):
  print("His last name is " + kid["lname"])

my_function(fname = "Tobias", lname = "Refsnes")
```
## Example Output
His last name is Refsnes
