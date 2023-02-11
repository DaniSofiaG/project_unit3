# project_unit3

![The Wonderful World of Japan’s Incredible Convenience Stores](https://user-images.githubusercontent.com/111941990/218233255-1c0c1ab4-c711-4ab8-b310-7a1c23530967.jpeg)


# Criteria A: Planning


## Problem definition
Meisa is the manager of a convenience store. Last year while doing the end of year report for the store in Decedmber she realized how tiering and disorganized was the process. It took her nearly 2 weeks to collect all the data she needed from excels document, receipts, memory and paper inverntories. Its also come to her attention that a lot of her staff struggles to put record the data properly because of the amount of different methods they have to learn and becuase of how tideous it is. This year she wants things to be different, that's why she's asked for a program that allows her to store and manage all the important data like product, supplier, aisles and staff information. She also has to be able to add or change data as the year goes on. The program has to be simple to use and choherent so that all staff is able to use it.



## Proposed Solution
Considering the client requirements an adequate solution includes a low cost sensing device for humidity and temperature and a custom data script that process and anaysis the samples acquired. For a low cost sensing device an adequate alternative is the DHT11 sensor[^1] which is offered online for less than 5 USD and provides adequare precision and range for the client requirements (Temperature Range: 0°C to 50°C, Humidity Range: 20% to 90%). Similar devices such as the DHT22, AHT20 or the AM2301B [^2] have higher specifications, however the DHT11 uses a simple serial communication (SPI) rather than more eleborated protocols such as the I2C used by the alternatives. For the range, precision and accuracy required in this applicaiton the DHT11 provides the best compromise. Connecting the DHT11 sensor to a computer requires a device that provides a Serial Port communication. A cheap and often used alternative for prototyping is the Arduino UNO microcontroller [^3]. "Arduino is an open-source electronics platform based on easy-to-use hardware and software"[^4]. In additon to the low cost of the Arduino (< 6USD), this devide is programable and expandable[^1]. Other alternatives include diffeerent versions of the original Arduino but their size and price make them a less adequate solution.


**Design statement**

I will design and make a program that checks temperature and humidity for two clients who are roommates and students at UWC ISAK Japan. The program will consist on a tool called DHT11 sensor for being able to keep track of humidity and temperature of their rooms, plus getting useful measures such as mean, standard deviaton, minimum, maximum, and median. It is constructed using the softwares Python, Arduino, and DHT11. It will take 3 weeks to make and will be evaluated according to the criteria A, B, and C.
