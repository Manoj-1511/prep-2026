#Count of Matches in tournament.
class Solution 
{
    public int numberOfMatches(int n) 
    {
        int Matches=0;
        while(n>1)
        {
            if(n%2==0)
            {
                Matches+=n/2;
                n=n/2;
            }
            else
            {
                Matches +=(n-1)/2;
                n=(n-1)/2+1;
             }
        }
          return Matches;
        
    }
}
