std::vector<long long> sequenceNumber(long long l, long long r)
{
    vector<long long> number;
    vector<long long> ans;
    for (int i = 1; i <= 9; i++){
        if (i > r) return ans;
        if (i >= l && i <= r) ans.push_back(i);
        number.push_back(i);
    }
    long long i = 0;
    while (i < number.size()){
        long long temp = number[i]*10 + number[i] % 10 + 1;
        if (number[i]%10 != 9 && temp <= r){
            number.push_back(temp);
            if (temp >= l) ans.push_back(temp);
        }  
        i++;
    }
    return ans;   
}
