

33. 
boolean found = false;
while(!found) {
    if(the keys are in the next place) {
        found = true;
    }
}

34. 
public void multiplesOfFive() {
    int num = 10;
    while(num <= 95) {
        System.out.println(num);
        num += 5;
    }
}

35. 
public void sumOneToTen() {
    int num = 1;
    int sum = 0;
    while(num <= 10) {
        sum += num;
        num++;
    }
    System.out.println("Sum = " + sum);
}

36. 
public int sum(int a, int b) {
    int total = 0; 
    while(a <= b) {
        total += a;
        a++;
    }
    return total;
}

37. 
public boolean isPrime(int n)
{
    if(n < 2) {
        return false; 
    }
    int divisor = 2;
    while(divisor < n) {
        if(n % divisor == 0) {
            return false; 
        }
        divisor++;
    }
    return true; 
}












