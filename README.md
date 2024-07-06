<h1>Software Architecture and Design Patterns - 2</h1>

<h2>Software Architecture</h2>
<p style="font-size: 22px;color: aqua">What is Software Architecture ?</p>
<p style="font-size: 22px">
<br>
<br>
fundamental structure of a software system
Software system එකක මූලික ව්‍යුහය.
<br>
<br>
Software system එකක තියෙන components, relations, system එකේ goals achieve කරගන්න ඒවා කොහොමද එකට වැඩකරන්නෙ කියල software එක ගැන High Level overview එකක් මේකෙන් බලාගන්න පුලුවන්. Software එකක් design/develop කරද්දි blueprint එක විදියට සලකයි.
</p>
<p style="font-size: 22px;color: aqua">Why is it important ?</p>
<p style="font-size: 22px">
<br>
<br>
Maintainability
Software එක Maintain කරන්න ලේසියි.
Software requirements හරිවිදියට fulfill වෙනවද කියල බලාගන්න පුලුවන්.
<br>
<br>
Risk management
Implement කරන්න කලින් software එක ගැන idea එකක් ගන්න පුලුවන් නිසා කලින්ම risk එක analyse කරන්න පුලුවන්.
<br>
<br>
Easy Team Collaboration
Team එකේ අනිත් අයට software එක ගැන තේරුම්ගන්න ලේසි කරයි.
</p>
<p style="font-size: 22px;color: aqua">Types of software architecture</p>
<p style="font-size: 22px">
1 Monolithic Architecture
<br>
<br>
A single, self-contained application where all components are tightly integrated into a single codebase.
Resource Oriented Architecture
Focuses on resources (data or services) accessible via URLs, often used in RESTful web services.
<br>
<br>
2 Client-Server Architecture
<br>
<br>
Splits the system into clients and servers, where clients request services or resources from servers.
<br>
<br>
3 Layered Architecture
<br>
<br>
Organizes the software into layers (ex: presentation, business, persistence, data) with defined interactions between them.
<br>
<br>
4 Microservices Architecture
<img src="./image/microservices.png" alt="" width="550px">
A modular approach where a software system is divided into small, independent services that communicate through APIs.
<br>
<br>
software system එකක්, API gateway එකක් හරහා communicate කරන කුඩා, තනි services වලට බෙදා ඇති modular approach එකක්.
<br>
<br>
<img src="image/Microservices1.png" alt="">
<br>
<br>
5 Space-based architecture (SBA)
<br>
<br>
<img src="image/img.png" alt="">
<br>
<br>
Network එකක, multiple nodes හෝ "spaces" හරහා data සහ processing බෙදාහරින architecture එකකි.
<br>
<br>
ex :  Google File System (GFS)
</p>
<p style="font-size: 22px;color: aqua">Role of software architecture</p>
<p style="font-size: 22px">
Requirements Gathering: Defines project objectives and requirements.
<br>
High-Level Design: Creates a blueprint for the system's structure.
<br>
Scalability: Supports system growth and adaptability.
<br>
Maintainability: Simplifies updates and bug fixes.
<br>
Reusability: Encourages component reuse.
<br>
Testing Support: Facilitates thorough testing.
<br>
Technology Adaptability: Allows for technology updates.
<br>
Risk Mitigation: Identifies and addresses potential risks.
<br>
Development Efficiency: Streamlines development tasks.
<br>
Team Collaboration: Fosters effective teamwork.
<br>
User Satisfaction: Ensures a positive user experience.
<br>
</p>
<p style="font-size: 22px;color: aqua">Application Architecture</p>
<p style="font-size: 22px">
Application Architecture vs. Software Architecture
<br>
<br>
<img src="image/img_1.png" alt="">
</p>
<br>
<p style="font-size: 22px;color: aqua">Software architecture characteristics</p>
<p style="font-size: 22px">
Software එකකින් අපේක්ෂිත qualities & properties නිර්වචනය කරන්න භාවිතා කරයි. (non-functional requirements)
<br>
වර්ග 2යි;
Structural
Quality attributes
<br>
<br>
Structural
<br>
Modularity ,
Layering,
Hierarchical decomposition,
Information hiding,
Encapsulation
<br>
<br>
Quality attributes 
<br>
Performance,
Scalability,
Reliability (විශ්වසනීයත්වය),
Security,
Maintainability
</p>
<p style="font-size: 22px;color: aqua">Quality driven attributes</p>
<p style="font-size: 22px">
Software system එකක overall quality එකට වැදගත් වෙන ගුණාංග
<br>
<br>
Performance,
Scalability,
Reliability ,
Security,
Maintainability ,
Usability,
Safety  ,
</p>
<p style="font-size: 22px;color: aqua">Introduction to Recurring(පුනරාවර්තන) Styles</p>
<p style="font-size: 22px">
Software development වලදි එන design & structural challenges විසදගන්න use කරන common patterns.
<br>
<br>
Recurring Styles in Software Architecture
වර්ග 4යි;
Creational,
Structural,
Behavioral,
Architectural
<br>
<br>
Creational Pattern
<br>
Object creation & instantiation ගැන focus කරයි. 
ex: Singleton, Factory Method, Abstract Factory, Builder, Prototype
<br>
<br>
Structural Pattern
<br>
Address how objects are composed to form larger structures.
ex: Facade, Adapter, Bridge, Composite, Decorator, Proxy
<br>
<br>
Behavioral Pattern
<br>
Objects interact & communicate ගැන focus කරයි. 
ex: Observer, Strategy, Command, State, Chain of Responsibility, Visitor
<br>
<br>
Architectural Pattern
<br>
මුලු system එකේම high-level organization & structure එක පාලනය කරයි.
ex: Model-View-Controller (MVC), Microservices, Layered Architecture
</p>
<p style="font-size: 22px;color: aqua">Design Patterns</p>
<p style="font-size: 22px">
Elegant solution to repeating problems in software design.
(Software හදද්දි නැවත නැවත එන ගැටළු වලට තියෙන විසඳුම්)
<br>
<br>
හැම Design Pattern එකක්ම, Code එකේ තියෙන problem solve කරගන්න use කරන්න පුලුවන් customizable blueprint වගේ.
Main types 3 යි;
<br>
<br>
Creational
<br>
Object creation ගැන තියෙන Design Patterns
Singleton Design Pattern,
Factory Design Pattern,
Prototype Design Pattern,
Builder Design Pattern,
<br>
<br>
Structural
<br>
Object අතර තියෙන relationships ගැන තියෙන Design Patterns
Facade Design Pattern,
Decorator Design Pattern,
Proxy Design Pattern,
Adapter Design Pattern,
Bridge Design Pattern,
Composite Design Pattern,
<br>
<br>
Behavioral
<br>
Object එකිනෙක අතර communicate කරන විදිය ගැන තියෙන Design Patterns
Observer Design Pattern,
Strategy Design Pattern,
Mediator Design Pattern,
State Design Pattern,
Memento Design Pattern,
Visitor Design Pattern,
Iterator Design Pattern,
</p>

<p style="font-size: 22px;color: aqua">1. Creational Design Patterns</p>
<p style="font-size: 22px">
Singleton Design Pattern
<img src="image/img_2.png" alt="">
Class එකෙන් හැදෙන්නෙ එක instance එකයි.
ඒ instance එක access කරන්න global access point එකක් ලබාදෙයි.
<br>
multi-threaded / multi-process environment වල single shared resource manage කරන්න use කරයි.
(configuration manager, database connection)
<br>
<br>
key components
<br>
<br>
1 private static instance
<br>
2 private constructor
<br>
3 public static method to get instance
<br>
<br>
Single Instance (private static)
Class එකකින් එක instance එකයි හදන්න දෙන්නෙ.(The key feature of the Singleton)
<br>
<br>
static <- එක instance එකයි හදන්නෙ. 
private <- direct access වළක්වයි.
<br>
<br>
Private Constructor
	new keyword එක දාල අලුතින් object හදන එක වළක්වයි.
<br>
Global Access (via public static Method)
හදන single instance එකට globally access කරන්න ක්‍රමයක් ලබාදේ.
<br>
<br>
Object එක create වෙන්නෙ එක පාරයි. ආයෙ instance එක ඉල්ලුවත් දෙන්නෙ එකම instance එක.
<br>
<br>
Factory Design Pattern
<img src="image/img_3.png" alt="">
<br>
<br>
Object creation logic එක hide කරයි.
<br>
objects create කරන්න interface එකක් සපයයි. (ShapeFactory)
<br>
subclasses වලට create කරන object වර්ගය වෙනස් කරන්න ඉඩ ලබාදේ. (Circle, Rectangle)
<br>
<br>
key components
<br>
Products (Product interface & Concrete products)
<br>
Factory (Factory interface & Concrete factory)
<br>
<br>
Products
<br>
factories වලින් හදන object. base class /interface එකකින්  products implement වෙලා තියෙන්නෙ.
<img src="image/img_4.png" alt="">
<br>
Factory Interface
<br>
Interface / abstract class එකක්. Object create කරන්න method එකක් declare කරයි. (method එකේ නම "create" හෝ “factoryMethod" වගේ එකක්)
<br>
Concrete Factories
<br>
factory interface එකෙන් implement වෙලා තියෙන්නෙ.
object creation method එකේ implementation එක තියෙන්නෙ මේක ඇතුලෙ. (Object creation logic එක තියෙන්නෙ මේකෙ)
<br>
Concrete class
<br>
A "concrete class" is a class with a complete implementation that can be instantiated to create objects. It provides specific code for all methods declared in interfaces or abstract classes it extends.
<br>
<br>
2 Decorator Design Pattern
<br>
<img src="image/img_5.png" alt="">
<br>
Runtime එකේදි, Existing object වලට new functionalities add කරන්න use කරයි.
Existing object එකේ code එක වෙනස් වෙන්නෙ නෑ.
<br>
අලුත් behaviors තියෙන special wrapper objects (decorator classes) ඇතුලට existing object දැමීම මගින් new functionalities add කරයි.
<br>key components
<br>
Component Interface<br>
Concrete Component(s)<br>
Decorator<br>
Concrete Decorators
<br>
<br>
Component Interface
<br>
Concrete components, decorators වලට තියෙන common interface එකක්. (or abstract class)
<br>
concrete components, decorators වලට implement වෙන්න ඕන basic operation(s) declare කරල තියෙන්නෙ මේකෙ.
<br>
<br>
interface Shape {<br>
    void draw();<br>
 }<br>
<br>
Concrete Component(s)
<br>
Component interface එකෙන් implement වුණු class. 
Extend / modify කරන්න ඕන core functionality එක තියෙන්නෙ මේකෙ.
<br>
Decorator
abstract class එකක් / interface එකක්.<br>
මේකත් Component Interface එකෙන් implement වෙලා තියෙන්නෙ.<br>
<br>
Component එකක් තියාගන්න පුලුවන් reference එකක් තියෙනො.<br>
Component වල behaviors modify කරයි / අලුතින් add කරයි.<br>
<br>
Concrete Decorators වලට common interface එකක් සපයයි.<br>
</p>








