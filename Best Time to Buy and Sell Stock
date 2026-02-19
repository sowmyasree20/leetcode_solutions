class Solution {
    public int maxProfit(int[] p) {
        int min=p[0];
        int max=0;
        int n=p.length;
        int i;
        for(i=1;i<n;i++){
            if(p[i]<min){
                min=p[i];
            }
        int pro=p[i]-min;
        if(pro>max){
            max=pro;
        }

        }
        return max;
    }
}
