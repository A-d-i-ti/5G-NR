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

1.**eMBB -** **Enhanced mobile broadband**
- emphasis of eMBB clearly is on higher speeds and spectral efficiency because as we know, higher spectral efficiency contributes ultimately to higher speed.
- ![image](https://github.com/A-d-i-ti/5G-NR/assets/142913419/14a5e6aa-ceac-4e0f-99ed-3731c312e2f9)
-  even if somebody is on a high-speed train that is moving at 100 or 200 miles an hour, they will expect high-speed broadband-like Internet to be available to them and eMBB is in a position to provide exactly that.
2.**MMTC Massive Machine Type Communications,**- known as _mIoT or massive IOT i.e INTERNET OF THINGS_
- mMTC is the umbrella that enables such electronic devices to communicate with the network and enter with each other.
- fundamental emphasis of mMTC is on power conservation and simplicity of protocols instead of spirit or spectral efficiency. 
- ![image](https://github.com/A-d-i-ti/5G-NR/assets/142913419/34d19ebe-f202-424a-ac9f-e7150eb97793)
- 
- This particular service class is meant for devices or applications that are mostly unmanned.
- For example, our phones or tablets are devices that we closely interact with on a daily basis.
3. **URLLC ,Ultra reliable, Low latency Communications.**- 
-URLLC is an umbrella that encompasses all the applications and use cases that require a highly reliable but at the same time low latency communication link.
-FOR EXAMPLE ,Military, first responders, law enforcement for all of those use cases every second counts,
-![image](https://github.com/A-d-i-ti/5G-NR/assets/142913419/615227e0-4125-4882-a5c0-fc5144ac7f62)
- emphasis is on minimizing end to end latency instead of emphasizing higher speeds.
- ### SOME TERMINALOGY :
- ![image](https://github.com/A-d-i-ti/5G-NR/assets/142913419/6a07e8d0-2ded-406f-bc91-c74e1167f762)
### DEPLOYMENT OF 5G NETWORK :
-We habe two options for deployment --> 1.STANDALONE  2.NON-STANDALONE 
- **STANDALONE,SA :** at one end you have a 5G phone which connects to a 5G gNodeB, which itself is a part of a wider 5G RAN, and the 5G RAN connects to a 5G core network also known as 5G C. So end-to-end, it is a 5G system. And because that end-to-end 5G system is capable of standing on its own, so to speak, that is the reason why this particular option of 5G network deployment is called a standalone option.
Not only are the costs related to hardware and software, but keep in mind that in order for the RAN to operate in 5G technology, you have to have some 5G spectrum associated with that RAN. And you have to buy or lease that additional 5G spectrum, which operators currently don't have at least._SO FOR THIS SITUATION WE HAVE NON-STANTALONE DEPLOYMENT ._
- **NON-STANDALONE DEPLOYMENT,NSA :** In a typical innocent network, operators can continue working with the existing 4G deployment. So operators who have 4G core network, which is called evolved packet core, will continue operating with that, and that 4G core network will connect with the nationwide deployment of 4G RAN.
- An NSA option allows you to have only a limited or surgical deployment of 5G gNodeBs in areas where you have severe capacity challenges which cannot be met by LTE.
- ![image](https://github.com/A-d-i-ti/5G-NR/assets/142913419/1de36dc6-73d6-4e65-a078-7c259671f1e9)
- SOME ANALOGIES :
- ![image](https://github.com/A-d-i-ti/5G-NR/assets/142913419/eab546ff-0bcc-42a5-98ee-0db5d870a561)
- **A flexible slot-based** framework, as the name suggest , is about making timelines a little flexible.
- frequency spectrum for those two seconds. Now, if the UE requires those two second. But what if the UE is faster than expected and it completes the task in just one second instead of two secondsAt least the resources corresponding to the remaining one second would be wasted because the UE has already completed its task. But that is where 5G makes all our operation more efficient in that not only does 5G allocate a given UE the precise amount of resources that will be needed to accomplish the task at hand.
- flexible slot-based framework is equivalent to flexible road framework, wherein lane markers can shift dynamically, and that ultimately allows us to efficiently adapt to all traffic types and situations within the existing amount of resources we have without using any additional resources.
- **OFDM Orthogonal Frequency Division Multiplexing:** OFDM allows you to send data not on wideband channels, but rather on multiple narrowband channels.
- OFDM allows you to use precisely the amount of bandwidth that you require and you have available and that it makes the whole system modular.
- scalable OFDM based air interface relates to a hypothetical road design where you can construct lanes out of Legos so to speak and you can add or subtract lanes on a given road precisely, depending upon the requirements of the oncoming traffic.
- **CHANNEL CODING :** Channel coding at a high level is about taking your intended data that the transmitter has in mind and wrapping it up, so to speak, in additional metadata.
   -  That way, even if some of that data gets corrupted because of noise interference and pathloss, by looking at the metadata and the original data together, the receiver can make 
      some educated guess about what the original data might have been
- **MIMO :** MIMO stands for multiple input, multiple output.
  - Input in this context is the number of antennas on the transmitters and output in this context is the number of antennas on the receiver. So if both the transmitter and the receiver, multiple antennas, the multiple input multiple output, it is said to be a MIMO system.
  -  nothing says that you have to be limited on either transmitter or receiver with just one antenna. What if both the transmitter and the receiver had one more antenna that was working in parallel.
  -  So instead of sending just one wireless signal between two devices, you are now trying to send to different wireless signals between the same pair of devices.
  -  It will significantly improve your data rate or speed or to put. And that is the fundamental premise of MIMO or multiple input, multiple output.
  -  **if you send two different signals on the same channel at the same time, you will have interference ???**
  -  to over come this interference problem ..two signals won't interfere with each other is because they are encoded by the transmitter differently.
  - **Massive MIMO** in that by transmitting multiple wireless signals at the same time using the same frequency channel. MIMO significantly **increases network coverage and capacity** and soldiers massive MIMO.
  - ![image](https://github.com/A-d-i-ti/5G-NR/assets/142913419/17af55d5-48f1-453f-9458-54ff37ea69b9)
  - **Software-Defined Networking,SDN :**  is about making your network more software-oriented than they were before. In that are trying to implement as many functionalities in a software and not just that, trying to implement them in generic software that could be compatible between different vendors.
  - With software-defined networking at a high level, the same underlying infrastructure because it is more software-oriented can be abstracted for different applications and network services.
  -  Not only does it make your system more resilient in that backward compatibility and interoperability is less of a problem and because you can have many different application or software developers working on that generic networking software,
  -  you also can benefit from rapid innovation in the entire ecosystem on account of the programmability that is offered by making these networks software-oriented
  -  **Network Functions Virtualization,NFV :** It allows to host that specialized hardware or a server firm, which turns out to be in the real networks that is deployment or offload it onto a Cloud network.
  -  _networking functionalities implemented as generic and broadly compatible software, that generic software can run on top of generic or as they call it COGS, **commercial off-the-shelf**_
  - The big advantage of making it into a Cloud is that you have **instant scalability.**
  -![image](https://github.com/A-d-i-ti/5G-NR/assets/142913419/7604495e-bbe0-4dfb-9cfa-aaec13b188d6)

- Because this cloudification, so to speak, is completely transparent with the end devices, as long as you maintain the performance guarantees between the 5G network and your Cloud providers' network, you should be able to provide reliable end-to-end 5G service without hosting a coordinate work yourself because your coordinate work is now sitting somewhere in the Cloud. That is the fundamental Internet of network function virtualization.
- **EDGE COMPUTING :**
- Edge computing is an emerging computing paradigm which refers to a range of networks and devices at or near the user.
-![image](https://github.com/A-d-i-ti/5G-NR/assets/142913419/937401a0-ea85-4b4f-bea9-9a8a3cf97c35)

-Edge computing can easily facilitate services that require extremely strict bounds on latency, that require enhanced security, as well as additional bandwidth.
- **5G utilizes in order to improve the network performance features such as network slicing, software-defined networking and network function virtualization, and mobile Edge computing or MEC.**
****************************************************************************************************************************************************************************************
### The 5G NR  :
- we have the proverbial low bands that are under 1 Gigahertz, also informally known as Sub-1 GHz. Some of the example bands in which 5G could be deployed here are bands like 600 MHz, 700, or 850 MHz.
- #### Millimeter wave mmWAVE :
- Millimeter wave simply is a certain range of frequencies where your signal **wavelength is on the order of a few millimeters**. That's why the name millimeter wave.
- there aren't any competing technologies in the millimeter wave spectrum, any technology that can successfully use the millimeter wave spectrum is going to have the proverbial first-mover advantage so to speak and it is going to have access to unprecedented amount of spectrum in other millimeter wave region.
- Millimeter wave is about improving your technological capabilities and prowess so that you are now able to utilize some of the frequency spectra that were earlier unused and because they are unused, you will have access to abundant bandwidth in those frequency ranges on the order of 400 or 800 megahertz at a time.
-  That enormous bandwidth directly translates to significantly higher individual user speeds and in aggregate manner, significantly higher network capacity.
- ![image](https://github.com/A-d-i-ti/5G-NR/assets/142913419/4edbe887-af4e-4244-b803-1e73acd786bb)
+ **THE 5G NR SPECTRUM:**
- ![image](https://github.com/A-d-i-ti/5G-NR/assets/142913419/5ce2de77-5c15-43b4-b145-5ae338fb9832)
- the basic disadvantage of **licensed spectrum**, its cost is cut by a significant margin when you share spectrum with multiple player
- with respect to **unlicensed spectrum**,it offers a good trade off between cost and performance.
- ![image](https://github.com/A-d-i-ti/5G-NR/assets/142913419/4c9b3453-a667-4cf8-a324-bb8719c1975b)
*****************************************************************************************************************************************************************************************
### EVOLUTION OF RADIO ACCESS NETWORK : 
-![image](https://github.com/A-d-i-ti/5G-NR/assets/142913419/0830b654-e60b-430e-b8a8-c09b101836f8)
-![image](https://github.com/A-d-i-ti/5G-NR/assets/142913419/8907761a-87d1-4606-8dce-fcaeff0a32e5)
The concept of layerization in cellular networks in a typical ran or base station or in this specific case based band unit. It's not a homogeneous black box, but rather there are multiple layers of responsibility within BBU each layer has a unique functionalities and responsibilities. And one of those responsibilities is to make certain decisions and pursuant to that decision, go on the behavior of all the bottom layers. That is one common functionality of all the multiple layers that exist within a BBU. And in logical terms it is no different from a typical corporation




