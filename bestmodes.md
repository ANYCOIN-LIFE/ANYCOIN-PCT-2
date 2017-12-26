#### Best Modes

[0028] 	The technical terms used herein are to simply mention a particular exemplary embodiment and are not meant to limit the present disclosure. An expression used in the singular encompasses the expression of the plural, unless it has a clearly different meaning in the context. In the specification, it is to be understood that the terms such as “including” or “having” etc., are intended to indicate the existence of specific features, regions, numbers, stages, operations, elements, components, or combinations thereof disclosed in the specification, and are not intended to preclude the possibility that one or more other specific features, regions, numbers, operations, elements, components, or combinations thereof may exist or may be added.


[0029] 	Unless otherwise defined, all terms used herein, including technical or scientific terms, have the same meanings as those generally understood by those with ordinary knowledge in the field of art to which the present disclosure belongs. Such terms as those defined in a generally used dictionary are to be interpreted to have the meanings equal to the contextual meanings in the relevant field of art, and are not to be interpreted to have idealized or excessively formal meanings unless clearly defined in the present application

[0030] 	Hereinafter, preferred embodiments of the present disclosure will be described in detail with reference to the accompanying drawings.

[0031] 	

[0032] 	FIG. 1 is a view illustrating an overall configuration of a virtual money funding system according to an embodiment of the present disclosure.  Referring to FIG. 1, the virtual money funding system according to an embodiment of the present disclosure may include a company terminal 10, an investor terminal 20, a consumer terminal 30, and a store terminal 40 on the user side using the virtual money investment system of the present disclosure and may include an initial coin offering (ICO) server 100, a financial server 200, and an exchange server 300, which are connected to the terminals 10, 20, 30 and 40 through a communication network and provide a user with a virtual money investment service.

[0033] 	In order to perform the functions of the present disclosure, the company terminal 10, the investor terminal 20, the consumer terminal 30, and the store terminal 40 may include a certain number of or combination of a processor, a controller, an integrated circuit, a programmable logic circuit, or any other database and signal processing device, and further include one or more memories, transmitters and receivers, displays, and communication modules capable of communicating with various devices.  In addition, the company terminal 10, the investor terminal 20, the consumer terminal 30, and the store terminal 40 may include a computer program performing a data operation through a designated algorithm and displaying a result of the operation through a display so that the result may be recognized from the outside, and a user interface (UI) implemented to allow a user to operate.

[0034] 	In the virtual money funding system of the present disclosure, the computer program includes a plurality of code segments executable in the company terminal 10, the investor terminal 20, the consumer terminal 30, and the store terminal 40 to perform each step.  Here, each step of a virtual money funding method may be performed according to order illustrated in the drawings but may also be performed in different order unless explicitly stated.  Also, some of the steps may be performed simultaneously and some of the steps may be performed selectively.

[0035] 	The company terminal 10, the investor terminal 20, the consumer terminal 30, and the store terminal 40 may include an electronic device accessible to one or more general-purpose computing resources such as Internet services, e-mail services, data transfer services. Also, the company terminal 10, the investor terminal 20, the consumer terminal 30, and the store terminal 40 may include a user database storing user-specific information for accessing online resources via a communications network, and the database may store any other information and data required for implementing the virtual money funding method of the present disclosure.

[0036] 	The company terminal 10, the investor terminal 20, the consumer terminal 30, and the store terminal 40 may include a mobile communication device (including a wireless device), a work station, a desktop computer, a laptop computer, a palmtop computer, a tablet computer, a portable digital assistant (PDA), a mobile terminal, a scanner, a kiosk, a printer, or any combination thereof.  In particular, the mobile terminal may include voice or data communication devices such as cellular phones, cell phones, smartphones, notebook computers, and the like.

[0037] 	The communication network connecting the company terminal 10, the investor terminal 20, the consumer terminal 30, and the store terminal 40 to the ICO server 100, the financial server 200, and the exchange server 300 may be a wired or wireless network, and may include electrically conductive cables or optical cables, as well as servers, routers, switches, wireless receivers and transmitters, and the like.  The communication network may also include the Internet or any other cloud network, as well as a local area network (LAN), a metro area network (MAN), or a wide area network (WAN). In addition, the communication network may include a landline phone network, a public switched telephone network (PSTN), an optical fiber network, and the like, as well as a cellular or mobile telephone network.

[0038] 	The company terminal 10, the investor terminal 20, the consumer terminal 30, and the store terminal 40 may all be connected to the communication network.  The company terminal 10, the investor terminal 20, the consumer terminal 30, and the store terminal 40 may communicate with other terminals via the communication network and may include appropriate components for establishing a wired or wireless connection.

[0039] 	The computer program for performing a virtual money funding method of the present disclosure may be executed in the company terminal 10, the investor terminal 20, the consumer terminal 30, the store terminal 40, the ICO server 100, the financial server 200, and the exchange server 300.  As such, a first portion of a program, a code, or an instruction may be executed in the company terminal 10, the investor terminal 20, the consumer terminal 30, and the store terminal 40, while a second portion of the program, the code, and the instruction may be executed in the ICO server 100, the financial server 200, and the exchange server 300.  In some embodiments, other portions of the program, the code, and the instruction may be executed in other electronic devices.  For example, information specific to each user may be stored in a memory of the ICO server 100, and thus, information specific to each user may be remotely accessed by a user or a manager using the computer program through one or more of the company terminal 10, the investor terminal 20, the consumer terminal 30, and the store terminal 40.  In an embodiment of the present disclosure, a portion of information implementing the present disclosure may be stored in the ICO server 100, while the other portion of the information may be stored in one or more of the company terminals 10, the investor terminal 20, the investor terminal 30, and the store terminal 40.

[0040] 	In an embodiment of the present disclosure, the computer program may be implemented as a stand-alone program installed in the company terminal 10, the investor terminal 20, the consumer terminal 30, and the store terminal 40 or as a web-accessible program that can be accessed by the company terminal 10, the investor terminal 20, the consumer terminal 30, and the store terminal 40 through the communication network.  In the case of the stand-alone program, a downloadable version of the computer program may be stored, at least in part, in the ICO server 100.  The user may download at least a portion of the computer program to the company terminal 10, the investor terminal 20, the consumer terminal 30, and the store terminal 40 via the communication network.  The computer program performing the virtual money funding method of the present disclosure may be an application such as an app for the company terminal 10, the investor terminal 20, the consumer terminal 30, and the store terminal 40.  After the computer program is downloaded, the program may be installed in an executable format in the company terminal 10, the investor terminal 20, the consumer terminal 30, and the store terminal 40.  The program in the executable format allows the user to access the embodiment of the present disclosure via electronic resources, such as mobile apps or websites.  In the case of the web accessible computer program, the user may simply access the computer program via the communication network using the company terminal 10, the investor terminal 20, the consumer terminal 30, and the store terminal 40.

[0041] 	The ICO server 100 serves to recruit investors for initial coin offering (ICO) of a company, issue an ICO token according to an investment amount, and determine an exchange ratio between the ICO token and an item token such that an item (goods/services) of the company which conducts ICO may be purchased  using the ICO token.  The ICO token may be considered as electronic securities whose value corresponds to a value of a virtual money investment amount of an investor.  To this end, the ICO server 100 may include a virtual money management system 110 which manages transactions of virtual money, an ICO token system 120 which manages issuance of ICO tokens and an exchange ratio between the ICO tokens and item tokens, and an investment management system 130 which manages an investment status of the ICO company and distributes a profit to an investor according to the performance of the ICO company or a management performance of virtual money.

[0042] 	In addition, the ICO server 100 invests the entirety of a portion of virtual money collected through ICO in a company (or a corporation), a subject of ICO, and may invest a portion of virtual money in a financial product to make profits.  In the case of investing the collected virtual money in the financial product, the ICO server 100 may interwork with the financial server 200.  Thus, the financial server 200 may be a component which can be connected through the communication network when the ICO server 100 invests virtual money in the financial product, and in case where the collected virtual money is entirely invested in the corresponding corporation and not invested in a financial product, the financial server 200 may be omitted.  Thus, the exchange server 300 may directly be connected to the ICO server 100 or may be connected to the ICO server 100 via the financial server 200.

[0043] 	Meanwhile, the exchange server 300 allows an ICO token and an item token including virtual money to be exchanged according to an exchange ratio at a specific point in time.  The exchange server 300 may be a server manufactured for the purpose of exchanging the ICO token and the item token or may be a server capable of trading virtual money including the ICO token and the item token together.  Basically, the exchange server 300 may apply an exchange ratio at the time of exchanging virtual money, the ICO token, or the item token.  The ICO token is virtual securities issued to investors through ICO, and a value thereof may be varied depending on a value of the corporation.  Therefore, when an item of the corresponding cooperation is directly purchased using ICO token, a purchase rage of the icon is changed according to fluctuation of the value of the ICO token, involving an unstable factor.  Thus, in order to purchase an item of the cooperation at a fixed value, it may be effective for the corresponding cooperation to issue an item token fixed at an exchange ratio with an item and the ICO token is allowed to be exchanged with the item token issued in the cooperation so as to be used in the exchange server 300.

[0044] 	

[0045] 	FIG. 2 is a view illustrating an internal configuration of an ICO server in a virtual money funding system according to an embodiment of the present disclosure. Referring to FIG. 2, the ICO server 100 of the present disclosure may include the virtual money management system 110, THE ICO token system 120, and the investment management system 130.

[0046] 	The virtual money management system 110 is a part for managing a collected amount of money and virtual money invested by an investor regarding ICO of a specific cooperation.  In detail, the virtual money management system 110 receives virtual money from the investor terminal 20 for an investment in a corporation that has applied for ICO and manages, and if necessary, the virtual money management system 110 may trade retained virtual money through the exchange server 300.  Accordingly, the virtual money management system 110 may manage a virtual money status by linking the ICO cooperation which has applied ICO with a virtual money investor status.  Meanwhile, in order to retain and trade virtual money, the virtual money management system 110 may retain an electronic wallet.  Here, in order for the virtual money management system 110 to perform a virtual money transaction, the electronic wallet of the virtual money management system 110 and an electronic wallet of the investor may be connected or electronic wallet information may be registered in the exchange server 300.

[0047] 	In particular, virtual money using a block chain such as Ethereum may have an error in transactions.  Such an error may occur when generation of transaction data has been attempted but failed, when transaction data has been generated but transaction is not made due to insufficient gas limit, or when a transaction is not completed due to an environment factor of an address for receiving virtual money, and the like.  The transaction data may not be generated as transaction requests are excessively made at a specific point in time to result in that transaction data itself is not generated or generation of transaction data is delayed.  Here, in case where transaction data is generated again with the same value, if the transaction data is generated with time delay, the same transaction data may be repeated.  In the case of the insufficient gas limit, a transaction may be canceled in spite of a transaction request.  Also, an error in an address for receiving electronic money may occur when large-scale transactions occur simultaneously.  In order to prevent such a transaction error, the virtual money management system 110 of the present disclosure may be implemented by separating an interface layer for receiving and processing a request signal regarding a user’s virtual money transaction and a database layer determining validity of the virtual money transaction and separately managing valid transaction data.

[0048] 	

[0049] 	FIG. 3 is a view illustrating a hierarchical structure of the virtual money management system of the ICO server in the virtual money funding system according to an embodiment of the present disclosure.  Referring to FIG. 3, the interface layer of the virtual money management system 110 may include an outside API processing a request transmitted from the company terminal 10 or the investor terminal 20 and an inside API checking validity of a transaction through a virtual money network.  The outside API checks an address and a status of a corporation or an investor and processes information such as a transaction request, transmission details, balance, and the like, including investment in virtual money, according to a request from the corporation or the investor.  The inside API creates a transaction log table in which a transaction request is made on the basis of the request information.  The transaction log table is data on which the transaction request is made and is data before validity of the transaction is checked.  The data on which the transaction request is made may have a transaction error due to various reasons.  Thus, when there is a transaction request from the company terminal 10 or the investor terminal 20, the inside API pre-processes the transaction request and records it in the transaction log table. Thereafter, when it is confirmed whether the transaction of virtual money has been validated with a predetermined delay time or validity of a server or a node handling the transaction of virtual money is confirmed, the inside API finally confirms the transaction details.  Here, the process of confirming validity of the transaction is preferably asynchronously processed in order not to match it to a time interval of generating a block chain of virtual money.  Through this process, a separate valid transaction table is created for transaction information of the transaction confirmed in validity.  Therefore, the data finally confirmed in transaction is managed as a valid transaction table, and a virtual money status of the ICO server 100 is changed according to the valid transaction table.  Regarding the transaction log table information pre-processed according to the transaction request, if information is not confirmed in validity within a predetermined time, the transaction remains pending, rather than being confirmed, and if validity confirmation is not checked within an expiration date (e.g., one day), the company terminal 10 or the investor terminal 20 may be informed accordingly and the pre-processing result may be canceled.

[0050] 	

[0051] 	Meanwhile, the ICO token system 120 is a part that manages a status of issuance of ICO tokens to an investor who has invested in virtual money for the ICO company which has applied for ICO, and manages an exchange ratio between an item token capable of purchasing goods or services of the ICO corporation and an ICO token.  In order to recruit virtual money investment, a company (or a corporation) which applies ICO may access the ICO server 100 and log in for membership, and after the company is authenticated as a member, the company may provide information for applying for ICO.  Here, the information input by the ICO company may include information regarding a name or a status of the company which applies ICO, enterprise constituent information such as a member, or the like, a funding amount to be recruited through ICO, and goods or services of the company.

[0052] 	The ICO token system manages a status of the ICO company which has issued ICO by linking it to an investor status.  An item token is issued by the ICO company or the ICO server 100 at the request of the ICO company, and a value of the item token is kept uniform, compared with a prices of goods of the ICO company.  Here, the item token may be issued in a plurality of types according to the contents of the ICO company’s goods or services, and since the item token aims at purchasing goods or services of the ICO company, it is not allowed for transactions between individuals.  Therefore, since an investor or a consumer who holds the item token may purchase goods at a fixed rate (price), the user may purchase goods at a fixed rate, regardless of fluctuation in value of virtual money from the user’s point of view of the item token.  Meanwhile, a value of the ICO token may vary depending on fluctuation in value of virtual money.  Therefore, although the value of the item token used for purchasing goods is fixed, compared with goods, the ICO token may be changed in conjunction with the value of virtual money, and therefore, goods may be purchased through the fixed exchange means (item token), regardless of value of virtual money, on the side of the purchaser.


[0053] 	The investment management system 130 is part handling a status of investors who have invested virtual money, investment details of the investors, a profit distribution according to investment, and the like, with respect to the company which has applied ICO.  Thus, the investment management system 130 manages the status of the investors who have invested virtual money and an investment amount of virtual money of each investor in conjunction with ICO company status data.  In addition, the investment management system 130 distributes profits to investors on the basis of sales and operating earnings on quarter, semiannual, and yearly basis of a specific ICO company.  In this case, the profit distribution may be made according to the invested virtual money amount, or the profit distribution may be made on the basis of ICO tokens generated according to the invested virtual money amount.  In other words, if an investor, who has invested 1 million won worth of virtual money in a specific ICO company and has been provided with ICO tokens corresponding thereto, uses the ICO tokens to purchase goods of the corresponding company, profit distribution may be made on the basis of ICO tokens of the balance.  In addition, the ICO server 100 may invest the entirety or a portion of virtual money collected through ICO in an ICO company or a financial product, and in this case, the ICO server 100 may distribute profits obtained therethrough to the investor.

[0054] 	

[0055] 	FIG. 4 is a flow chart illustrating a process of issuing and managing an ICO token in a virtual money funding method according to an embodiment of the present disclosure.  Referring to FIG. 4, ICO token management according to ICO may include receiving an ICO application (S121), registering ICO company information (S122), recruiting ICO investors (S123), issuing an ICO token corresponding to a virtual money amount (S124), determining an exchange ratio between the ICO token and an item token (S125), and providing the exchange ratio to an exchange server (S126).

[0056] 	In step S121 of receiving an ICO application, a company that wants to collect an investment amount based on virtual money may apply for ICO to the ICO server 100 using the company terminal 10, and the application is received.  Requirements of a company for applying for ICO may be determined by an industrial field, types of goods or services of the company, the number of members of the company, past sales performance, and the like, and any company registered as a business operator may apply for ICO, without extra requirements.

[0057] 	In step S122 of registering the ICO company information, the company which has applied for ICO inputs related information to recruit a virtual money investment.  Here, the information input by the company which has applied for ICO may include basic information such as company performance and members, an investment amount to be collected through ICO, and information about characteristics and business feasibility of goods or services of the company.

[0058] 	In step S123 of recruiting ICO investors, candidate investors who will invest virtual money in the company which has applied for ICO are selected and information on the ICO company which has applied for ICO is provided to the candidate investors to induce virtual money investment.  Step S123 of recruiting ICO investors in performed in conjunction with the investment management system 130, and thus, step S123 will be described in detail when an operation process of the investment management system 130 is described.

[0059] 	In step S124 of issuing an ICO token corresponding to a virtual money amount, an ICO token corresponding to the investment amount is issued to the investor who has invested virtual money in the ICO company.  The issued ICO token may be in the same ratio as that of invested virtual money amount or may be in a different ratio.  Since the exchange ratio between the amount of ICO token provided through investment in the ICO company and virtual money is determined, the investor which has received the ICO token may exchange the ICO token with virtual money or with an item token for purchasing goods of the ICO company as necessary in the future.

[0060] 	In step S125 of determining the exchange ratio between the ICO token and the item token, a ratio for exchanging the ICO token provided according to an investment amount of virtual money regarding the ICO company with an item token issued by the ICO company is determined.  The ICO company conducting ICO issues an item coupon that may be used for purchasing goods or services of the ICO company.  The item coupon has a certain percentage of value that matches a real price of goods or services of the ICO company.  For example, an item coupon with an exchange ratio of 1,000:1 to the price of an ICO company's goods or services may use the ICO company’s goods or services at a price of KRW 1,000 for one item coupon.  Here, an investor retaining an ICO token may exchange it with an item token to use goods or services of the ICO company. Therefore, a corporation conducting ICO determines an exchange ratio with the ICO token to be issued to an investor participating in an investment in ICO, while issuing an item token corresponding to the price of goods or services. Such an exchange ratio may be determined to reflect the value of virtual money at the time of investing in the ICO company through ICO, or a specific exchange ratio may be fixed at the time of ICO.

[0061] 	In step S126 of providing the exchange ratio to the exchange server, the exchange ratio is provided to the exchange server 300 so that the investor holding the ICO coupon may exchange the ICO coupon with an item coupon issued by the ICO company.  When there is an exchange request between the ICO coupon and the item coupon from the investor or the consumer, the exchange server 300 may exchange the ICO coupon and the item coupon according to the exchange ratio provided from the ICO server 10.

[0062] 	

[0063] 	FIG. 5 is a flow chart illustrating a process of handling a funding management system in a virtual money funding method according to an embodiment of the present disclosure.  Referring to FIG. 5, an investment for a company applying for ICO includes extracting candidate investor information (S131), delivering ICO company information to the candidate investor (S132), receiving virtual money investment information (S133), delivering an investment result to the ICO company (S134), and distributing a profit according to performance (S135).

[0064] 	In step S131 of extracting candidate investor information, a candidate investor related to the company which has applied for ICO is extracted from the investor data stored in the investment management system 130.  Here, as the candidate investor, a company or an individual who has an investment result of virtual money in relation to the ICO company or who engages in a field related to the ICO company or an investor who has designated a specific field as an investment interest field may be extracted with priority from the investment management system 130.  In addition, if the company which has applied for ICO designates a desired amount of investment, the number of candidate investors may be limited in consideration of an amount investable per investor

[0065] 	In step S132 of delivering the ICO company information to the candidate investor, information about the company which has applied for ICO is delivered to the extracted candidate investor.  Here, the candidate investor may determine whether to invest in the corresponding company and an amount of investment by referring to the delivered ICO company information.

[0066] 	In the step of receiving the virtual money investment information (S133), information regarding whether to invest and the amount of investment is received from the terminal 20 of the candidate investor.  In case where one of candidate investors determines to invest virtual money in the ICO company, information regarding the invest participation and the amount of investment is received from the investor terminal 20, and in case where the candidate investor determines not to invest, information regarding investment rejection may be received from the investor terminal 20.

[0067] 	In step S134 of delivering an investment result to the ICO company, after the completion of ICO investment conducted for the candidate investor, an investment result is generated by collecting information regarding a status of investors participating in the virtual money investment and an amount of investment and delivered to the ICO company or the investors participating in investment.  Here, the investment result may be written in a report form and delivered to the ICO company or investors or the ICO company or the investors may access the ICO server 100 and read the investment result.

[0068] 	In step S135 of distributing a profit according to performance, a profit is distributed to the investors participating in ICO according to sales result of goods or services of the ICO company.  Therefore, this step may be performed by reflecting the performance of ICO company’s goods or services after the completion of the virtual money investment.  Profit distribution may vary on the basis of, for example, the number of investors participating in the ICO investment, the number of sold goods, or the sales of goods.  Here, the profit may be distributed on the basis of the amount of invested virtual money or the amount of the ICO token issued to the investor to correspond to the invested amount of virtual money.  Also, the ICO server 100 may invest the entirety or a portion of the virtual money collected through ICO in an ICO company or a financial product, and distribute an obtained profit as a result to the investors.

[0069] 	

[0070] 	FIG. 6 is a view illustrating an internal configuration of an ICO server in a virtual money funding system according to an embodiment of the present disclosure.  Referring to FIG. 6, the ICO server 100 of the present disclosure may include a database 170, at least one central processing unit (CPU) 160 connected to the database 170 and performing a high-speed operation, an input device 140, and an output device 150.

[0071] 	Here, the input device 140 may be a device such as a mouse or a touch screen capable of recognizing a user’s operation or touch, and may also include a physical transducer such as a microphone.  The output device 150 refers to a display capable of displaying characters or images such as a light emitting diode (LED), a liquid crystal display (LCD), and an electronic ink (e-ink), or may include  a transducer such as a speaker.

[0072] 	The CPU 160 is embedded in the ICO server 100 and performs a function of processing an overall operation.  That is, interworking with the company terminal 10 which wants to apply for ICO, the investor terminal 20, the consumer terminal 30, and the store terminal 40, the CPU 160 applies for ICO of an ICO company, issues an ICO token, and performs investment management process. The CPU 160 may include an arithmetic logic unit (ALU) 162 for performing calculation, a register 164 for temporarily storing data and instructions, and a controller 166 for controlling an operation of the ICO server 100.  The CPU 160 may be a processor having a variety of architectures including Alpha from Digital, MIPS from MIPS Technology, NEC, IDT, Siemens, and others, x86 from Intel and others, including Cyrix, AMD, and Nexgen, and the PowerPc from IBM and Motorola.

[0073] 	The database 170 generally includes a high speed main memory 172 in the form of a storage medium such as a random access memory (RAM) and a read-only memory (ROM), an auxiliary memory 174 such as flash memory, and a device for storing data using electrical, magnetic, optical or any other storage medium.  Also, the main memory 172 may include a video display memory displaying an image through the output device 150. It will be apparent to those skilled in the art that the database 170 may have various forms as a product having various storage capabilities.

[0074] 	In the technical field of the present disclosure, the ICO server 100 may include an operating system (OS) and at least one application program.  The OS is a set of software that controls an operation of the ICO server 100 and assignment of resources. An application program is a set of software for performing a task requested by a user by using available computer resources through the OS.  The application program may be, for example, a virtual money management program, an ICO token management program, and an investment management program.  The OS and application programs will reside in the database 170.  Unless stated otherwise in accordance with the experience of those skilled in the art of computer programming, the present disclosure will be described in accordance with an operation performed by the ICO server 100 and representation symbols regarding the operation.  Such an operation may be computer-based and may be performed by an OS or a suitable application program.  Also, such an operation and function include processing of the CPU 160 on an electric signal such as a data bit, or the like, causing conversion or interruption of the electrical signal and management of a data bit signal stored in a memory area within the database 170, as well as changing an operation of the ICO server 100.  The memory area in which the data bit signal is managed is a physical area having electric, magnetic, or optical characteristics corresponding to data bits.

[0075] 	

[0076] 	Although the specific exemplary embodiments of the present disclosure have been described with reference to the accompanying drawings, it will be apparent to a person skilled in the art to which the invention pertains that various changes in forms may be made without departing from the spirit or essential features of the present disclosure.  Therefore, the foregoing specific embodiments are intended to be illustrative in all aspects rather than limiting. The scope of the present disclosure shall be defined by the appended claims rather than the foregoing description and it should be interpreted that the present disclosure shall extend to all modifications or changes derived from the definition, ranges, and equivalents of the claims.

[0077] 	10: company terminal 	20: investor terminal

[0078] 	30: consumer terminal 	40: store terminal

[0079] 	100: ICO server		110: virtual money management system

[0080] 	120: ICO token system	130: investment management system

[0081] 	140: input device 		150: output device

[0082] 	160: CPU			162: ALU

[0083] 	164: register		166: controller

[0084] 	170: database		172: main memory

[0085] 	174: auxiliary memory