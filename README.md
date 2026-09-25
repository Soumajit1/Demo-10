class Solution {
public:
    int numTrees(int n) {
        vecclass Solution {
public:
    int lengthOfLastWord(string s) {
        int i = s.size() - 1;
        while (~i && s[i] == ' ') {
            --i;
        }
        int j = i;
        while (~j && s[j] != ' ') {
            --j;
        }
        return i - j;
    }
};
public:
    int numTrees(int n) {

class Solution {
public:
    int searchInsert(vector<int>& nums, int target) {
        int l = 0, r = nums.size();
        while (l < r) {
            int mid = (l + r) >> 1;
            if (nums[mid] >= target) {
                r = mid;
            } else {
                l = mid + 1;
            }
        }
        return l;
    }
};




class Solution {
public:
    int searchInsert(vector<int>& nums, int target) {
        int l = 0, r = nums.size();
        while (l < r) {
            int mid = (l + r) >> 1;
            if (nums[mid] >= target) {
                r = mid;
            } else {
                l = mid + 1;
            }
        }
        return l;
    }
};
