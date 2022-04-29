# Challenge WIF 500
![wif500](https://user-images.githubusercontent.com/82582647/163708843-3ba05950-7c30-4d44-bec0-c7bc26616188.jpg)</br>
**Find the key, get 200 BTC donations!**</br>

The known part of the key is 40 characters from 52</br>
The address [1PfNh5fRcE9JKDmicD2Rh3pexGwce1LqyU](https://www.blockchain.com/btc/address/1PfNh5fRcE9JKDmicD2Rh3pexGwce1LqyU) 500 btc</br>

You can search yourself in [WifSolverCuda](https://github.com/phrutis/WifSolverCuda)</br>
If you are lucky, you can donate coins to the BTC address: 1HUAWqBHkTNuSLMyCUBXBA3DoPstpMyoyv</br>
### But before that, read the following:</br>

The problem is people's greed.</br>
Everyone wants to search individually to take possession of all the coins, this is logical.</br>
The range of missing symbols is very very large and everyone is spinning the same thing.</br>
Some lone hunters make the mistake of rotating ranges that don't exist, further increasing the empty search time.</br>
Sometimes they make other mistakes that make finding the key impossible.</br>
After a week of searching, they begin to realize that the range is too large.</br>
It is difficult and physically impossible to go through it, they will be disappointed, angry, and stop searching.</br>

### Challenge is a collective search for a key
A large range of 12 characters is divided into 3364 small ranges</br>
The program is configured correctly, it takes into account many technical aspects of searching for the initial part of the key.</br>
There is a table of hunters on which ranges are indicated in the process and passed. This way you won't pass empty ranges. </br>
This speeds up the overall search process.</br>
The advantage of the challenge is that if the key is found, each hunter will receive compensation for the range he has passed.
Donate 200 btc is a worthy reward for a find key.</br>
You decide. Good luck!</br>

## How to participate in the challenge:
If you have a GPUs:</br>
**RTX 2070, 2080, 2090, 3060, 3070, 3080, 3090, A5000, A6000** and are ready to search for a key **24/7**</br>

If you do not have a 30xx card, you can [**rent**](https://vast.ai) it and participate in a collective search. </br>
For some users, [renting](https://vast.ai) is cheaper than searching on their own PC. There is also less noise in the house.</br>
When renting, you must take into account the risk that the key may not be found at all. You may incur losses.</br>
Think of it not as earnings, but as a lottery.

In the [**TABLE**](https://github.com/phrutis/wif500/blob/main/x64/Release/table.md), select a **FREE** range between 0-3363

Run ```wif500-20xx.exe -range 1234``` (free range 0 - 3363)

RTX A6000 4 Gkey/s = 4 days (one range)</br>
RTX 3090 4 Gkey/s = 4 days (one range)</br>
RTX 3070 2.2 Gkey/s = 6 days (one range)</br>
RTX 2070 1,4 Gkey/s = 9 days (one range)</br>
There is a continuation of the search from the last checkpoint</br>

Add a telegram [**GPU group**](https://t.me/+WFEuFatijpowMjRi) </br>
Write: @phrutis the numbers of the range in which you took for the search.</br>
I will accept your participation and add you to the table</br>
Do not take busy (in progress) ranges, see the [**table**](https://github.com/phrutis/wif500/blob/main/x64/Release/table.md).</br>
**Don't join if**</br>
1. Your gpu is below RTX 2070</br>
2. You are just interested, but you are not going to participate either.</br>
3. Ask questions not related to the challenge.</br>

When you have a range progress 100% take a screenshot (photo) and post it in the group. </br>
I will (check) and mark the range as passed, assign it to you.</br>

If the key is found, it will be displayed in the window and will also be written to the text file FOUND.txt
Write privately in telegram: @phrutis that you found the key.

### Compensations:

 1. When the key is found, the hunter that did find it will receive a full 200 BTC reward.</br>
 2. To the rest of the hunters, for every range completed, a 0.01 BTC  (410 usd) reward (to cover the electricity costs and not mining all that period) will be paid after the key is found.</br>
Total reward equals to 33.64 (0.01 BTC/range x 3364 ranges).

### Rules:

 1. Do not counterfeit  the proof. Send genuine screenshot, search honestly - if you fake it and the key was in your range, everybody loses!
 2. If the key is found in early stages, that amount of 33.64 BTC for all the 3364 will be split among the hunters that have completed range searches.</br> Example: Hunters completed cumulatively 1000 ranges at the time the key was found.</br> 
The 33.64 BTC will be divided to those 1000 completed ranges, resulting in 0.03364 BTC (~1337 usd) for each completed range scan.


### Frequently asked Questions:

WIF real?</br>
To find out, you need to go through a very large range and find out.</br>
This requires large GPU resources.</br>

Why is the program without source codes?</br>
The correct ranges and other parameters are sewn into the WifSolverCuda program.</br>
Knowing them, the user can find the key on his own and take everything for himself.</br>

Does the program require an internet connection?</br>
No, the program is looking for the key offline.</br>

If I find the key can I take all the coins for myself?</br>
No, you will find the encrypted key.</br>
Only the organizers of the challenge can decrypt this key and pay you a donation.</br>

There is a video in which there is a similar key.</br>
There are errors in the video that make the key impossible to find.</br>

I have many GPUs. How to start?</br>
Run each GPU separately with a new range Add your card id -d ?</br>
For RTX 2070, 2080, 2090, 3060, 3070, 3080, 3090, A5000, A6000</br>
```wif500-30xx.exe -range 444 -d 0```</br>
```wif500-30xx.exe -range 445 -d 1```</br>
```wif500-30xx.exe -range 446 -d 2```</br>
```wif500-30xx.exe -range 2057 -d 3```</br>
```wif500-20xx.exe -range 888 -d 4```</br>
If you have any difficulties with the launch, you can ask in the group




