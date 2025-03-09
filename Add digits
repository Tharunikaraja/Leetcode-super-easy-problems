int addDigits(long long int num) {
   long long int s=num;
    while (s>9) {
        num=s;
        s=0;
        while (num != 0) {
            s=s+num% 10;
            num=num/10;
        }
    }
    return s;
}
