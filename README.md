# DigitSum
A program that calculates the sum of the digits of a number.
* For e.g. 1643 = 1 + 6 + 4 + 3 = 14

## Scope Block Sample

```
 do {
            System.out.println("Please enter a number: ");
            num = input.nextInt();
            if (num >= 0) {
                asknum = true;
            }
        }
        while (!asknum);

        fakenum = num;

        while (fakenum != 0) {
            digitval = fakenum % 10;
            result += digitval;
            fakenum /= 10;
        }


        System.out.println("The sum of the digits of the number "+num+" is: "+result);
```
