# Verify your temperatures

Why is this lesson next? I cannot tell you how many consults I have done, how many individuals I have spoken to where their CPU is idling at 60c and then they launch a game and it's shooting up to 80/85c, they're getting thermally throttled and then they wonder a few months later. "Why is my CPU degraded?" and this is why. CPU temperatures are VERY important. 

# What are common causes of high CPU temperatures?

- Builders leaving the cover sticker on their new AIO heatsink
- Poor thermal paste spread
- Wrong fan orientation
- Using wrong standoffs

We want to make sure that we are getting our temperatures to a manageable level before anything else because if we have bad CPU temperatures, bad VRM temperatures, bad RAM temperatures, bad GPU temperatures, it's just going to make the optimisation pointless. 

# Step 1: Enter the BIOS

How to do you know if you have bad contact? Well, once you enter the BIOS, the temperatures will slowly climb. It'll start at 40c, then 42c, then 44c, then 48c and so on and this is a sign that your CPU is not properly mounted and/or not properly seated and this is what is causing those fluctuations in temperature and you want to address this immediately. So how does this happen? The IHS is getting heat soaked and the heat soak is not being transferred to the CPU cooler, again, this needs to be remedied immediately. 

# Step 2: Enter Windows on stock settings

- Load up your preferred PC monitoring software, I prefer HWInfo64 but if you prefer AIDA64? Then use that instead.
- Locate CPU Package/CPU diode and monitor this sensor, this is the one that we are going to be monitoring throughout these tests.

# Step 3: Stress testing your CPU

1: Using AIDA > Overclocking icon at the top of the program (fire symbol) > Untick all apart from "Stress System Memory and then click "start". This is good because although it is a RAM stress test, it will hit the CPU at very low power draws and perfect for starting our CPU stress test process. 

2: Again, using AIDA we want to head to the overclocking section of the application and run a "CPU" stress test, so click "CPU" > Start and leave it for 5-minutes and see how it performs, look at the heat, see if it stablises and stays 'flat'.

3: Finally, we're going to throw something a little bit more heavy at the CPU. This where XTU, Prime95 or OCCT comes in. Choose whatever you're most comfortable with, give it a further 5-minutes and see how things progress from there. Again, make sure that your temperatures stablise and go from there.