# Practice with Pull Requests

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Person A:

Person A should modify content here.

## Person B:

Person B should modify content here.

## Person C:

Person C should modify content here.

## Person D:

# A pair (i,j) is called good if nums[i] == nums[j] and i < j.

# Return the number of good pairs.


def num_identical_pairs(nums)
  hash = {}
  pairs = 0

  nums.each do |num|
    if hash[num]
      hash[num] += 1
    else
      hash[num] = 1
    end
  end
puts hash

  hash.each do |k, v|
 
      pairs += (v * (v-1)) / (2)

  end
  return pairs
end


nums = [1,2,3,1,1,3, 3]

puts num_identical_pairs(nums)

## Person E:

Person E should modify content here.

## Need inspiration?

Need inspiration for what kinds of files to make or change?

Try:

- Copying and pasting your favorite poem!
- Put in a file of your latest CS Fun homework
- Just say "hi" for someone to see!
