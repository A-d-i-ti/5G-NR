# 5G-NR
hey there ! this my understanding of 5G NR technology.
### WIRELESS COMMUNICATION: 
Wireless communication allows transfer of information between a transmitter and a receiver without a physical medium.
wireless communication does not need a physical medium. It can travel just as well in a vacuum space.
*a typical wireless communication system has four fundamental components*;**A transmitter, a receiver, a wireless signal, and a fourth imaginary entity that is called a wireless channel.**
+ **TRANSMITTER**- The entity that is looking to transmit some data to the other end over a wireless medium, that will be called the transmitter.
+ **RECEIVER** - The entity that is looking to receive that data will be called the receiver.
- our antennas are also an integral part of any transmitter or receiver, because that is what helps you send or receive wireless signals.
+ **WIRELESS SIGNALS-**  Wireless signals are also called Radio-frequency signals.
- All wireless or radio signals are quite similar in nature to sunlight or visible light, at such all wireless signals travel at the speed of light, which is approximately 300,000 kilometers per second.
- Two basic attributes of radio frequency signals --->  frequency and wavelength
+ _Frequency :_ Frequency is the number of repetitions that the periodic electromagnetic signal undergoes in a given second, and the frequency is measured in the unit of hertz. 
+ _WAVELENGTH :_ Wavelength is the distance that periodic wireless signal travels during one cycle or one periodicity, and because it is a measure of distance, it is mostly measured in meters or millimeters.
+  wireless signals are interchangeably also called radio signals or radio frequency or RF signals because the frequency of those wireless signals happens to lie between the range specified by the traditional radio frequency range.
+ _HOW DO WE COMMUNICATE OVER A NETWORK :_
+  These periodic RF signals or wireless signals are also known as **carrier waves** because they carry the information from one end to the other.
+   RF signals are used as the so-called vehicle for information transfer because they carry your information from the transmitter to the receiver.
+  **Modulation** - is a process by which we impress or impose information onto the carrier wave for transmission.
+  Modulation at the high level is about carefully changing some of the specific attributes of the radio-frequency signal.
+  At the receiver, however, the other end of wireless communication, we need to extract that information from the incoming carrier wave.
+ **DEMODULATION :** Demodulation is the process of recovering the data that has been impressed upon the carrier wave by the transmitter.
+ *MODEM* stands for modulation and demodulation and is the device used for the same .
+ _HERE IS A SIMPLE TELEPHONIC CONVERSATATION FOR OUR UNDERSTANDING : REFER THE IMAGE BELOW_
+ ![image](https://github.com/A-d-i-ti/5G-NR/assets/142913419/ccd9c8eb-ff6f-4aee-9507-64086d884847)
**WIRELESS CHANNEL-** The imaginary channel over which those wireless signals go from one point to another called either the wireless channel or the radio channel.
- Radio frequency signal travels over the air and when it travels over the air it faces certain **impediments**. The most important and most significant of which is called attenuation or part loss or **transmission loss**.
- **Transmission loss**- The wireless signal has to spend some energy when going from one point to another.The manifestation of that loss of energy is quantified in technical terms as part loss or transmission loss.
- SIGNAL FROM OUR PHONE ----> CELL TOWER -----> RECEIVER'S PHONE
- The transmission loss or path loss is a roughly proportional operational frequency.
- Higher the frequency of operation, higher the corresponding path loss will be.
- IN SIMPLE WORDS -_Higher the frequency of the radio signal higher the pathloss that it encounters when going from one point to another._
- **Impediments that affect a wireless signal** -noise and interference
- **NOISE -** Noise is unwanted energy that is not deliberate in nature.
- In that the wireless noise or the electromagnetic noise is always present in most devices and most communication links. In fact, some of the noise can be one generated within the communication device itself, also known as **thermal noise**.
- The ambient noise which is always present and cannot be minimized beneath a certain threshold .
- **INTERFERENCE -** when two nearby transmitters and nearby is the key, when they use the same radio frequency at the same time, they create interference.
- Interference is deliberate in nature and can be mitigated by careful planning of the frequency use by different entities in the network.
- Noise and Interference have a tendency to **Change some of the fundamental attributes** of the electromagnetic carrier wave so that it becomes little difficult for the intended receiver to demodulate and extract the intended information from the signal that has slightly been changed in form because of noise and interference.
- ![image](https://github.com/A-d-i-ti/5G-NR/assets/142913419/c3253189-f3a3-472e-9d66-a27f6c83f76b)

-  Noise and interference have a tendency to reduce the quality of the signal that is ultimately received .
- SNR - SIGNAL NOISE RATIO gives us an mathematical estimation of the noise present .
- SINR - SIGNAL INTERFERENCE NOICE RATIO gives us an mathematical estimation of interference as well as noise present .
- ![image](https://github.com/A-d-i-ti/5G-NR/assets/142913419/3c68b468-fe6a-40e8-b139-9d124a0e4b10)
### RADIO SPECTRUM : 
Radio spectrum essentially is just the range of radio frequencies over which a wireless communication takes place, for a specific purpose.
- ![image](https://github.com/A-d-i-ti/5G-NR/assets/142913419/564d6641-55f0-47d9-9e75-8d4b27c861f3)
- **There are some regulatory entity whose job it is to carefully assign dedicated slices of radio spectrum to different services.**
- In case of United States, that government regulatory entity is the **FCC or Federal Communications Commission**
- _It is the local regulatory authority that determines what spectrum will be used by what service, for what purpose._
-  **channel bandwidth / frequency channel**- limited range of frequencies over which a wireless device, exchanges wireless or radio signals, it's called its frequency channel.frequency channel currently being used by a wireless device, it's called the channel bandwidth.
-  ![image](https://github.com/A-d-i-ti/5G-NR/assets/142913419/1d15cec6-15fe-47a0-b5c1-65ccfee5991c)
- _**what prevents every channel from being a wideband channel? **_
-  **Availability** is the primary reason why every channel can't be wideband. frequency spectrum is limited by definition
- **COST** Being extremely expensive because spectrum is inherently a scarce and expensive commodity
-  #### MULTIPLE ACCESS OF RADIO CHANNEL : 
-  There are defined algorithms that allow sharing of the radio channel and that translates to a concept of multiple access. multiple access allows us to achieve that desirable trade off between the cost of the frequency spectrum you need to operate your system. multiple access involves carefully leveraging some of the attributes of the wireless channel.
- Two ways to share the limited and expensive spectrum -**Frequency division duplexing [FDD]and Time division duplexing [TDD]**
- **Frequency division duplexing ,FDD**- it stands for frequency division duplexing, entails and requires rather a pair of radio channels for simultaneous two-way communication. For example, if you have abundant frequency spectrum, you could allocate one channel on which your cell tower would transmit. You could allocate a different independent frequency channel on which your phone would transmit.  
- ![image](https://github.com/A-d-i-ti/5G-NR/assets/142913419/d024d922-8108-4a8a-a270-13792f36200c)
- **Disadvantage of this FDD mechanism** is that you have to have enough budget in order to buy two separate frequency channels. Not only that, your local regulatory authorities have to have abundance spectrum available in order to allocate two independent channels for your system.One for downlink, one for uplink.
- **Time division duplexing ,TDD**-TDD system has access to only one frequency channel. There are no two frequency channels anymore. Both the base station and your phones have to operate on the same frequency channel.
- Single radio channel is the basic characteristic of a TDD system.
- ![image](https://github.com/A-d-i-ti/5G-NR/assets/142913419/71abd90c-9b98-4342-a008-af9287f56d80)

#### CELLULAR CONCEPTS :
A mobile network's coverage area is divided into what are called cells, the small areas which are called cells.That is where the name cellular communication or cellular network derives from.
- Because the area is covered into many different cells of small size and each of those individual cells is served by what is known as a **Base station**.
- t is also known as the **cell tower or simply the tower**.
- ![image](https://github.com/A-d-i-ti/5G-NR/assets/142913419/3be15b8d-aa84-4c0f-aeae-d71b78d44845)
-
-   WE have to maximize the data rate and coverage area while keeping the number of base stations at a minimum.
-   CELLULAR NETWORK :consists of -->RAN {RADIO ACCESS NETWORK},CORE NETWORK & SERVICES .
-  ![image](https://github.com/A-d-i-ti/5G-NR/assets/142913419/2b410e1f-799a-4d6f-9d90-e3d589f5a553)
 
- **RADIO ACCESS NETWORK,RAN** : The RAN comprises multiple base stations or cell towers and these are the entities as we have seen that exchange wireless signals with your phone.
- **CORE NETWORK :**it is supposed to be the routing bridge between your phone and the services network .it acts as the middleman between your phone and the services network.
- *********************************************************************************************************************************************************************************
- ### EVOLUTION OF 5G :
- **first generation of cellular communications, i.e 1G.**-  In the 1970s and '80s with what is retroactively now known as the *first generation of cellular communications, i.e 1G.** 
     The predominant use case at that time was to enable people to make and receive voice calls on the go wherever they were.
- In the first generation of cellular communications, our analog voice was imposed onto the outgoing carrier wave using analog modulation.
- **SECOND generation of cellular communications, i.e 2G.**- The fundamental focus was still on providing voice services but now you will see a different qualifier and that is for a 
   well-merited reason. But in the second generation of cellular communication, the modulation technique that would be used to super-impose our voice onto the outgoing carrier wave would be digital modulation.
- **THIRD generation of cellular communication, i.e 3G.**-gave us seamless access to mobile Internet for eg:news or weather forecast, or be it as specialized and complex as video broadcast, audio broadcast, or email.the speeds were somewhat limited compared to what we have today on the order of few 100 Kbps or a few Mbps.
- **FOUTH generation of cellular communication, i.e 4G, also known as LTE**-4G not only improved the speeds that it would offer to your mobile phones, but it also greatly expanded the Ecosystem beyond just everyday phones into the realm of tablets, smart home device, fitness trackers, etc. That was the fundamental power of 4G in that it expanded our ecosystem.
- **FIFTH generation of cellular technologies, i.e 5G.-** ultra high speeds and ultra high network capacity.will absolutely require low lag or low time delay so that they can offer real-time and interactive experience to their users, like VR or augmented reality.
- #### MORE ABOUT 5G :
-  5G also known as NR or new radio.5G NR is expected to provide us with unprecedented levels of capability and efficiency.
-  ![image](https://github.com/A-d-i-ti/5G-NR/assets/142913419/52483fc1-fc5b-4ad8-b7ea-3763957d5fa1)
-  ### 5G NR Service Classes :
-![image](https://github.com/A-d-i-ti/5G-NR/assets/142913419/55fb7bf8-9ad0-409d-8db8-1fd5a921ded4)
