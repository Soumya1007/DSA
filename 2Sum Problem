class Solution {
public:
    vector<int> twoSum(vector<int>& nums, int target) {
       int n=nums.size();
        vector<int>v;
        unordered_map<int,int>mp;
     
        for(int i=0;i<n;i++)
        {
            if(mp.find(target-nums[i])!=mp.end())
            {
                v.push_back(i);
                v.push_back(mp[target-nums[i]]);
            }
              mp[nums[i]]=i;
        }
     
        return v;
    }
};
