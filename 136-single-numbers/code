class Solution {
public:
    int singleNumber(vector<int>& nums) {
        // XOR operator: 1 1 - 0 : 0 0 = 0 : 1 0 - 1 : 0 1 - 1
        int ans = 0;
        for(int val : nums) {
            ans  ^= val;
        }
        return ans;
    }
};
