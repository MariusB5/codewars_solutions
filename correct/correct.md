# Correct the mistakes of the character recognition software

Character recognition software is widely used to digitise printed texts. Thus the texts can be edited, searched and stored on a computer.

When documents (especially pretty old ones written with a typewriter), are digitised character recognition softwares often make mistakes.

Your task is correct the errors in the digitised text. You only have to handle the following mistakes:

* ```S``` is misinterpreted as ```5```
* ```O``` is misinterpreted as ```0```
* ```I``` is misinterpreted as ```1```

## Given Code

```python
def correct(s):
    pass
```

## Sample Tests

```python
from solution import correct
import codewars_test as test

@test.describe("Example tests")
def _():
    @test.it("Example tests")
    def _():
        test.assert_equals(correct("L0ND0N"), "LONDON")
        test.assert_equals(correct("DUBL1N"), "DUBLIN")
        test.assert_equals(correct("51NGAP0RE"), "SINGAPORE")
        test.assert_equals(correct("BUDAPE5T"), "BUDAPEST")
        test.assert_equals(correct("PAR15"), "PARIS")
```
