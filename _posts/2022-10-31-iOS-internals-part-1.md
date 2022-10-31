## iOS internals

Hey, because it's my first blog post then ill introduce myself, I'm a security researcher who mainly focused on iOS research and also a CS undergrad, I love math and the economy as so maybe from 
time to time ill upload some posts about quantative finance.
also i like boxing,surfing,snowboarding,and eating.

this is going to be a series abouts iOS internals, i dont know how many parts im going to make to this series(i am going to try as many as i can)

its going to be general knowledge from user-space view diving into kernel-space view and digging into apple badass architact, as well as mostly and propely exclusvlity looking at it from a security perpctive(how mitagation works, how they handled and handling active research on their OS and winning ): )

so to start we are going to look on the *OS architecture from very very shallow perspective.

apple os is pretty complex, maybe even the most complex one i takled.

there is 5 layers for the architecture 
Application Layer
media 
core services
core os 
kernel and drivers
