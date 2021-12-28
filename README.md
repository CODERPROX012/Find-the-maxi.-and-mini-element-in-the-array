pair<long long, long long> getMinMax(long long a[], int n) {
    pair<long long int ,long long int>p;
    long long int temp=0;
    long long int temp1=1000000000000;
    
    for(int i=0;i<n;i++)
    {
        if(temp<a[i])
        {
            temp=a[i];
        }
        if(temp1>a[i])
        {
            temp1=a[i];
        }
    }
    p.first=temp1;
    p.second=temp;
    
    return p;
}
