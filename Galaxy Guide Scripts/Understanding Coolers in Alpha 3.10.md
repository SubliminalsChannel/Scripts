
# Understanding weapons and components
## Components Guide
### Preface
We're gonna take an in depth look into coolers and we're starting right now.

### Introduction
Thanks to all the support from Patrons and Channel Members it takes a while to make one of these and your support is appreciated.
Welcome to "A Star Citizen’s Guide to the Galaxy" What's up Citizens, this is SubliminaL here and In this guide I will explain my Understanding of how coolers work on paper, including, Cooling Rate, Max Cooling Rate, and how Draw Request Time Effects Cooling. Then I'll show some tests I completed live on twitch to see how these metrics effect your components and ship. Spoiler Alert they don't do shit, well they do but you probably don't need to upgrade them. I may be completely wrong about some of the info in this guide and that's OK because we are all learning throughout our journey in Star Citizens Alpha that is constantly changing. The pinned comment will be used to ensure accuracy. This is Part 2 of a series that will cover each archetype of component and weapon in depth. So Make sure your subscribed and have the bell clicked for more. Enough with the formalities, let's get to it.

### Overview
Regardless of the testing shown here today Coolers are an important component for your ship in Star Citizen. After all if you power them down... this happens. Your ship is now dead and will need an insurance claim to be operational again. PSA to new players please note the RSI website is not recommended as a source for current and updated information on ships, components, or weapons. I highly recommend Erkul.Games for up-to-date info that is gathered straight from the games data.

### Cooling Rate
To understand how cooling works in star citizen think of heated coolant flowing into a cooler. Your cooling rate is how much coolant is currently being cooled by your coolers. To understand cooling rate lets take a look at a sabre build I made over at Erkul.Games, we'll be looking at the stock bracer coolers. Your cooling rate is listed here in white. This rate is not static it depends on a lot of things, luckily erkul has these things toggleable. As you can see maneuvering, firing, and whether or not your shields are charging is a huge factor in how much coolant will be pushed through to your coolers. Amongst other factors that don't pertain to this particular ship.
If Cooling Rate is the amount of coolant being cooled then you guessed it Max Cooling rate is the maximum amount of coolant the cooler can handle. This is static and only changes if you change your coolers. If you exceed this capacity then you will have issues, the best way to know you have insufficient cooling is if you hear any of these. (Shields Over heating, Engines Overheating, Systems Overheating). To make sure this doesn't happen just plug your build into erkul and if you see this, you should make some changes before heading out into the verse. If not your good to go. Also erkul does not factor in overclocking so if you plan too, its best to leave yourself some headroom. Back to the coolers The problem is the pipes that lead into your components cannot be changed by using a different cooler. The size of these pipes are determined by the component or weapon itself. So by thinking that upgrading your coolers will lengthen the time before your weapons overheat you are essentially asking for the ship or the components pipes to be widened, and that's not currently possible. This is how the system currently works but there are plans to change this in the near future.

Small rant incoming, you can skip to the timestamp onscreen if you already know what I'm talking about. One thing I want to touch on really quickly is my use of the term "Kilo Per Second" The game files where erkul extracts his data from, state that the zero rush has a cooling rate of 283,000 since this is a video game there is no unit of measurement, code doesn't care about that. So when I say 238 Kilos per second I'm just simply saying there are 238 thousand thousands. Because saying or writing 238,000 cooling per second sounds kind of stupid. And it gets even stupider if your talking about the size 3 Chill Max coolers with 17,600,000 cooling... Now, since the surface of our son is 5,700 degrees kelvin I am inclined to believe this is not the case. And again since this is a video game it could be measured in cheese burgers for all I care. Sorry for the rant lets get back to it.

### Cooling & Request Time
Now for a more complicated part how Request Time effects your coolers. We'll be looking at Two coolers, the Quick Zero Rush's, and the Beefy Ultra Flow's.
The Zero Rush has a cooling rate of 238kilos/per second and a Request Time of 3 seconds. What you have to understand is from the start the zero rush do not cool at the rate of 238k it is actually cooling at an idle rate, if your powered up. Request time is the amount of time in seconds that it takes for the cooler to get from 0 to the max rate of 238kps. So for our example the Zero Rush will take a little less than 3 seconds to reach the 238k if going from idle to its max rate. Or the full 3 seconds from a cold start either because you just powered up your ship or starting to recover from an EMP.
Now Lets compare this to the Ultra flow. It has a max cooling rate of 440k/s and a Request Time of 8 seconds. Great cooling Rate but not so good request time.

While I have both of these coolers up with these fancy graphics let me talk about a common myth amongst the community. When you are splitting coolers or any  other component between 2 different coolers. Each cooler adds to the pool of max cooling rate. They work independently. For example if you pair the Zero Rush with an Ultra flow, the Ultra flow will not inherit the lower request time of the Zero Rush. This also applies to shields and power plants. This may have been the case multiple patches ago, but not now. Don't feel bad I actually assisted in spreading this rumor in some of my first recommended loadouts. I am sorry for this but now we know.

Anyway, Both of these are great coolers on paper. Lets see how these actually effect your ship in game.

### In-Game Cooler Testing.
The first test we'll be doing is an acceleration test. In this test I will be accelerating using full and constant afterburner to the Sabre's max speed of around 1235m/s. The audio you'll be hearing throughout these tests is from the stock cooler clip. These clips will end at the frame at which it reaches that speed. Watch Closely.

That was about 5 frames of difference.

The Next test was recorded seconds after the last and this shows how long it took the ships temperature to reach idle. During this test I am not giving the ship any input.

The difference here was 34 frames or half a second from best to worst.

Ok now lets see how long it takes to bring the ship to a complete stop using spacebrake. We will start when temperatures are stable while traveling at max speed. These clips Start at the Max Speed and end at the frame that shows 0m/s

That was a 4 frame difference

The next test is a quick one. According to wiki over at StarCitizen.Tools Coolers effect the distance you can quantum before overheating and the cooldown rate of your quantum drive. We already know we can travel across the system without overheating so well just test the later. I traveled from Port Tressler to MicroTech L1. The clips start when QT ended and end at the frame just before cooldown disappeared.

There was no difference even at 60 frames. Myth Busted. I think this info was from a past patch.

Next we'll test weapons. Lets just get this out of the way I was going to test ballistic Mantis's Gatling's but found out that they simply don't overheat. But ill let you hear it becuase it sounds good.

This is stock.

This is overclocked. Ohhh Yeahh... (Clear Throat) Sorry.

Now let's take a look at laser weapons. Well be looking at the size three CF series laser repeaters. The Clip will start when the first laser appears on screen and ends when the annunciator panel says the weapons have overheated.

That was a 33 frame or half second difference in the favor of the stock bracers.

Next is how long after the last test ended before the overheated light on the annunciator panel disappeared.

That was a single frame difference

For the Next Test as quickly as I could after they cooled down I started firing again until the panel says the weapons have overheated.

This was a full 2 second difference. But please note that I believe this is due to my reaction time between when the weapons where no longer overheated and when I started firing. Becuase the longer you wait after your weapons overheat the longer you will be able to fire before they overheat again.

And this next one is how long after that it took for them to cool down.

9 frame difference

Ok Subliminal what about overclocking? Well Lets see. Same as before first laser to overheated notification.

17 Frame difference

Now How long did it take them to cool down?

Single Frame difference again.

now that they have recovered how long can I fire until overheated again.

32 Frames

And finally how long until cooldown?

7 Frame difference

### My thoughts
Alright so what does all of this mean? Well it means coolers don't really do shit. I did not see much perceivable difference between each cooler. The most was a 2 second difference that I'm sure was a result of a slow reaction time on my part. So after doing this research I have concluded the following. There are 3 options you should go with when picking coolers. 1st is, if your stock coolers can handle your upgrades then there is no reason to upgrade them. If you still want to upgrade them then you have 2 options. Either go with grade 1 stealth coolers to get the lowest possible EM IR emissions or my personal favorite go with the lowest draw request time in case you get EMPd. The IR difference between coolers is negligible in my opinion but some builds may want to get every bit of stealth you can get your hands on. Of course all of this depends on weather or not the quick or stealthy coolers have enough capacity.


### Outro
I hope you've enjoyed this in-depth look into coolers. In Part 3 in this series will take an in depth look into power plants, it will be added to the info card, end screen and description once it's complete. Did I miss anything? let me know down in the comments. If you enjoy my channel there are 6 ways to support it, #1 you can smash that like button. #2 you can share this content with someone who may enjoy it. #3 you can check out my "locations of Stanton" collection over at Displate and in the Merch Store #4 You can follow me on Twitch I go live after almost every YouTube release Twitch Prime Subs help support the channel #5 you can subscribe and turn on notifications by clicking the circle here. And #6 if you're feeling generous, consider becoming a Channel Member or even better a Patron. Some Pledge perks can be seen here, Including desktop versions of my locations of Stanton collection available to all patrons and members. If not just sticking around until the end is greatly appreciated. Until next time Citizens, I'll see you in the verse.
