https://practice.geeksforgeeks.org/problems/count-digits5716/1

class Solution{
    static int evenlyDivides(int N){
        // code here
        int num=N;
        int count=0;
        while(N!=0)
        {
            int d=N%10;
            N/=10;
            if(d==0)
            continue;
            if(num%d==0 &&d!=0)
            count++;
           
        }
        return count;
    }
}
