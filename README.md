# Practice with Pull Requests

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Person A:

We're no strangers to love
You know the rules and so do I
A full commitment's what I'm thinking of
You wouldn't get this from any other guy
I just wanna tell you how I'm feeling
Gotta make you understand
Never gonna give you up
Never gonna let you down
Never gonna run around and desert you
Never gonna make you cry
Never gonna say goodbye
Never gonna tell a lie and hurt you

## Person B:

Person B should modify content here.

## Person C:

Christabel is person C and has so many secreeeettttttsss. But they're all in a .env so they're safe.

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
