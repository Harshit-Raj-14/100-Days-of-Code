class Solution
{
public:
    int reverse(int x)
    {
        int ans = 0;
        while (x != 0){
            int digit = x % 10;
            if (ans > INT_MAX / 10 | ans < INT_MIN / 10) return 0;  //we are using divide to make sure that if we had proceed with the next step the int will overlow
            else{
                ans = ans * 10 + x % 10;
                x /= 10;
            }
        }
        return ans;
    }
};
