# 选题报告——户外旅行设备 

## 成员
游豪毅：Yoki198
邓仕荃：Shiquan-Deng
杨鑫：keriong
景荟洋：Huiyang-Jing
李丹：Lindra-ld
黄旭鹏：WeiT167

## 1.问题定义 

    对于户外旅行来说，所处的位置有时候没有实时的环境（温湿度、紫外线强度等）数据，或者有时候会遇到没有网络信号的问题。为了为户外旅行者更方便做决策，需要能获取当前的环境信息的设备。但我们不仅需要获得环境的数据，还需要获得旅行者的身体状况数据和运动数据。设备可为用户提供一些数据，如运动量、运动轨迹、卡路里消耗、心率检测等。还可以综合考虑环境和旅行者的身体状况，为旅行者提供数据参考并且可以分析后提供参考意见。一方面可以让旅行者做出合理的决策、规划最优出行的时间；另一方面可以保障安全，紧急情况可开启紧急模式。所以我们的设备应该可以将环境数据监测和人体数据监测功能集成与一体 ，综合考虑稳定、轻便、长续航等特点，具有紧急模式特色的智能设备。  在分析了功能后，我们综合考虑后选择使用类似手环的产品模型，在这基础上搭载我们的特别功能和需求。使用温湿度传感器、紫外光传感器、心率检测等传感器实现对应功能。考虑使用触摸屏和各类元件。让旅行者更加了解自己的出行运动数据和环境数据，让旅行变得更加充满趣味。  对于户外旅行来说，所处的位置有时候没有实时的地理位置数据，经常有与队友走散，安全的风险。为了为户外旅行者更方便做决策，能获取当前的环境信息的设备显得十分重要。并且户外环境大多结伴而行，尤其在户外较为空旷的环境下，与队友走失的事情时有发生。有时候通讯设备联系时会遇到信号不好而无法联系，并且单纯使用语言等描述相对位置也十分困难。因此我们考虑开发一款专注于户外使用的手表，能够准确提供其他人的位置信息方位，并且可以在危机时刻上传呼救信号的手环。
   
 
## 2.需求分析

    智能手环作为目前备受用户关注的科技产品，其拥有的强大功能正悄无声息地渗透和改变 人们的生活。其内置的电池可以坚持10天，振动马达非常实用，简约的设计风格也可以起到 饰品的装饰作用。 智能手环这种设计风格对于习惯佩戴首饰的用户而言，颇具有诱惑力。更重要的是，手环 的设计风格堪称百搭。而且，别看小小手环个头不大，其功能还是比较强大的，比如它可以 说是一款高档的计步器，具有普通计步器的一般计步，测量距离、卡路里、脂肪等功能，同 时还具有睡眠监测、高档防水、蓝牙4.0数据传输、疲劳提醒等特殊功能。智能手环是一种穿戴式智能设备。通过这款手环，用户可以记录日常生活中的锻炼、睡眠 、部分还有饮食等实时数据，并将这些数据与手机、平板、ipod touch同步，起到通过数据指 导健康生活的作用。
  根据中研产业研究院《2020-2025年中国智能手环行业供需分析及发展前景研究报告》和调研机构IDC的数据显示，2019年第三季度全球可穿戴设备出货量共计8450万台，同比增长94.6%，创下单季度出货量的新纪录。华为，苹果，三星出货量增幅最大，均超过100%。
    IDC估算，苹果公司上季度的可穿戴设备出货量为2950万台，高于2018年第三季度的1000万台。苹果仍然是世界上最大的可穿戴设备供应商，AirPods Pro的推出和Apple Watch 3代手表的低价销售让苹果保持领先地位。 
  苹果的财报中并没有披露可穿戴设备的销售情况，因此应该强调，IDC的数据是第三方估算的的，但所有迹象都表明，Apple Watch和AirPods的销售非常好。 2019年第三季度，苹果“可穿戴设备、智能家居和其他配件”营收创纪录地达到65亿美元，较上年同期的42亿美元增长54%。在财报中，这个类别跟iPhone或iPad并行，除了Apple Watch、AirPods和Beats之外，这类别还包括了HomePod、Apple TV、iPod touch以及苹果品牌和其他配件等等。 
  AirPods Pro在推出后应该销量不错(虽然苹果也从没公布过它的销量)，用户目前预定都需要明年1月才能发货，从侧面表明新耳机有多受欢迎。小米手环 5 将于 6 月 11 日发布，今天官方公布了新品的 7 大升级。小米手环5的定妆照，采用椭圆外形，2.5D弧面屏幕，色彩丰富，手环颜色多达8种之多。 这七大升级分别是：加大号动态彩屏、专业传感器升级、磁吸式充电、11 种专业运动模式、NFC 银联闪付、全新女性健康模式、远程遥控拍照。 
  根据中研产业研究院《2020-2025年智能手环市场发展现状调查及供需格局分析预测报告》显示，小米手环 5 将首次支持控制手机拍照，除此之外，还将新增 5 种运动模式：瑜伽，椭圆机，划船机，跳绳和室内自行车，这也让其运动模式总数增加至 11 个。且小米手环 5 将支持通过 SpO2(血氧饱和度)测量来增强心率追踪，其它健康功能将包括月经周期跟踪等。 只有更大的屏幕，才能让每次抬手都更鲜活有趣;只有磁吸充电，才能让每一次充电都轻松快意;更少不了强大的NFC银联闪付、多项高精度传感器、11种专业运动模式及全新的女性健康模式。你以为这些升级就是全部了吗? 
  小米手环5在外观、体验、功能等各方面都有了很大的提升，接下来最大的悬念就是价格了，预计依然保持200元内。小米旗下广受欢迎的产品“小米手环”系列在本季度出货量超过1000万部，该公司通过瞄准欧洲、中东和非洲(EMEA)地区的国家，得以大幅扩大其全球影响力。 智能手环是一种穿戴式智能设备。通过智能手环，用户可以记录日常生活中的锻炼、睡眠、部分还有饮食等实时数据，并将这些数据与手机、平板、ipod touch同步，起到通过数据指导健康生活的作用。 智能手环作为目前备受用户关注的科技产品，其拥有的强大功能正悄无声息地渗透和改变人们的生活。其内置的电池可以坚持10天以上，振动马达非常实用，简约的设计风格也可以起到饰品的装饰作用。 尽管面临一些挑战，但由于在中国的强劲表现，华为的出货量在全球排名第四。在中国，华为同比增长188%，成为中国市场增长最快的公司之一。在世界其他地区，华为同样保持了强劲的增长。 Fitbit位列前五，公司最新推出的可穿戴设备和手表虽然受到欢迎，但出货量仅增长0.5%，谷歌的收购让该品牌的未来充满了不确定性。
  智能手环作为目前备受用户关注的科技产品，其拥有的强大功能正悄无声息地渗透和改变 人们的生活。其内置的电池可以坚持10天，振动马达非常实用，简约的设计风格也可以起到 饰品的装饰作用科技的进步会引领人们进入一个新的时代，智能手环将会开创下一个智能领域，其方便性为更多人所接受、使用。
    

## 3.概念设计 

### 3.1 设计理念

以人为本，坚持体现个性化与精神情感是我们核心的设计理念。服务用户，真正站在用户角度思考问题，是我们的出发点。个性化与精神文化在设计中的体现是我们一直以来注重的细节与创新点。体现出手表的服务功能是设计户外手环的第一要务。我们在设计时考虑引入相对距离，相对方位等概念，让队友的位置更加具象化，有助于寻找与定位；同时我们开发了两个版本的手环，加入了海拔，所处位置经纬度显示，心率等数据心事，以及多种配色与设计方案，满足人们个性化的选择，满足了个性化与美观的需求。

### 3.2 项目分析

    我们团队经过前期的市场调查与分析，选择了学生群体作为手环开发的目标用户群体。针对对市场上现有手环进行总结分析，发现市面上流行的手环大致可以分为两类：一种是偏向于手机的功能定位，手表体积大，功能丰富，售价昂贵，在一些场景下可以完全替代手机的功能；另一种是倾向于局部监测仪，主要用于监测心率，步数等，同时可以简单的显示时间以体现传统手表的功能。根据我们的市场调研结果来看，并没有一款专门针对户外旅行的，并且价格低廉的手表。
  我们的客户需求分析则展现了户外手表所需要的功能。我们的调查群体主要为大学生，根据问卷结果显示，大部分学生出行方式为结伴而行，即在户外常常是团队行动。这时候会经常面临团队走失的状况从而影响了整个团队的行程；而一旦发现小伙伴走失也是一件让人担忧的事情。因此我们计划开发出一款户外手环，上面可以显示出你和团队其他成员的距离以及所处方位，从而轻松确定队友的位置，让团队出行更加安全便捷。另外我们还考虑设计了“超范围报警器”，用户们可以自己设定报警器的报警范围，一旦有同伴超过了报警范围，手表将会发出蜂鸣声，来提示队友可能已经超出团队活动范围，规避走失或遇到危险的情况。


## 4.详细设计

### 4.1 物料清单
  2个lcd显示屏1602，2个GPS模块

### 4.2 主要功能与运行原理

   A，B两个各自从北斗卫星（GPS模块）接受各自的地理信息，同时A，B之间相互通信，将自己的地理信息传输给对方(esp32-s模块，lora模块)，通过处理A，B两个的信息，算出两个的相对位置，并显示出来（oled0.91模块）

### 4.3 代码 

  #include "U8glib.h"
#include <TinyGPS++.h>
#include <SoftwareSerial.h>
//如下是gps接受信息模块
TinyGPSPlus gps;
SoftwareSerial ss(4,3);//rx,tx

float latitude0;
float longitude0;
float latitude1;
float longitude1;

float distance;//两者之间的相对距离
void setup()
  {
    Serial.begin(9600); //set the baud rate of serial port to 9600;
    ss.begin(9600); //set the GPS baud rate to 9600;
  }
void initial(){
  latitude=0;longitude=0;}

void loop()
  {
   initial();
    while (ss.available() > 0)
      {
        gps.encode(ss.read()); //The encode() method encodes the string in the encoding format specified by encoding.
        
        if (gps.location.isUpdated())
          {
            latitude = gps.location.lat(); //gps.location.lat() can export latitude
            longitude = gps.location.lng();//gps.location.lng() can export latitude
            Serial.print("Latitude=");
            Serial.print(latitude, 6);  //Stable after the fifth position
            Serial.print(" Longitude=");
            Serial.println(longitude, 6);
            delay(500);
          }
        else{Serial.print("no data");}
      }
  }
//wifi通信模块。
#include <LoRaNow.h>
#include <WiFi.h>
#include <WebServer.h>
#include <StreamString.h>
#include <PubSubClient.h>
//vspi
#define MISO 19
#define MOSI 23
#define SCK 18
#define SS 5

//hspi
//#define SCK 14
//#define MISO 12
//#define MOSI 13
//#define SS 15

#define DIO0 4

const char *ssid = "MERCURY_E8A6 ";
const char *password = "yangxin115";

const char* mqtt_server = "broker.hivemq.com";

WebServer server(80);
WiFiClient espClient;
PubSubClient mqttclient(espClient);

const char *script = "<script>function loop() {var resp = GET_NOW('loranow'); var area = document.getElementById('area').value; document.getElementById('area').value = area + resp; setTimeout('loop()', 1000);} function GET_NOW(get) { var xmlhttp; if (window.XMLHttpRequest) xmlhttp = new XMLHttpRequest(); else xmlhttp = new ActiveXObject('Microsoft.XMLHTTP'); xmlhttp.open('GET', get, false); xmlhttp.send(); return xmlhttp.responseText; }</script>";

unsigned long lastMsg = 0;
#define MSG_BUFFER_SIZE  (60)
char msg[MSG_BUFFER_SIZE];

int value = 0;

void handleRoot()
{
  String str = "";
  str += "<html>";
  str += "<head>";
  str += "<title>ESP32 - LoRaNow</title>";
  str += "<meta name='viewport' content='width=device-width, initial-scale=1'>";
  str += script;
  str += "</head>";
  str += "<body onload='loop()'>";
  str += "<center>";
  str += "<textarea id='area' style='width:800px; height:400px;'></textarea>";
  str += "</center>";
  str += "</body>";
  str += "</html>";
  server.send(200, "text/html", str);
}

static StreamString string;

void handleLoRaNow()
{
  server.send(200, "text/plain", string);
  while (string.available()) // clear
  {
    string.read();
  }
}

void callback(char* topic, byte* payload, unsigned int length) {
  Serial.print("Message arrived [");
  Serial.print(topic);
  Serial.print("] ");
  for (int i = 0; i < length; i++) {
    Serial.print((char)payload[i]);
  }
  Serial.println();

  // Switch on the LED if an 1 was received as first character
  if ((char)payload[0] == '1') {
    //digitalWrite(BUILTIN_LED, LOW);   // Turn the LED on (Note that LOW is the voltage level
    // but actually the LED is on; this is because
    // it is active low on the ESP-01)
  } else {
    //digitalWrite(BUILTIN_LED, HIGH);  // Turn the LED off by making the voltage HIGH
  }

}

void setup(void)
{

  Serial.begin(115200);

  WiFi.mode(WIFI_STA);
  if (ssid != "")
    WiFi.begin(ssid, password);
  WiFi.begin();
  Serial.println("");

  // Wait for connection
  while (WiFi.status() != WL_CONNECTED)
  {
    delay(500);
    Serial.print(".");
  }

  Serial.println("");
  Serial.print("Connected to ");
  Serial.println(ssid);
  Serial.print("IP address: ");
  Serial.println(WiFi.localIP());

  server.on("/", handleRoot);
  server.on("/loranow", handleLoRaNow);
  server.begin();
  Serial.println("HTTP server started");

  LoRaNow.setFrequencyCN(); // Select the frequency 486.5 MHz - Used in China
  // LoRaNow.setFrequencyEU(); // Select the frequency 868.3 MHz - Used in Europe
  // LoRaNow.setFrequencyUS(); // Select the frequency 904.1 MHz - Used in USA, Canada and South America
  // LoRaNow.setFrequencyAU(); // Select the frequency 917.0 MHz - Used in Australia, Brazil and Chile

  // LoRaNow.setFrequency(frequency);
  // LoRaNow.setSpreadingFactor(sf);
  // LoRaNow.setPins(ss, dio0);

  LoRaNow.setPinsSPI(SCK, MISO, MOSI, SS, DIO0); // Only works with ESP32

  if (!LoRaNow.begin())
  {
    Serial.println("LoRa init failed. Check your connections.");
    while (true)
      ;
  }

  LoRaNow.onMessage(onMessage);
  LoRaNow.gateway();
  //mqtt
  mqttclient.setServer(mqtt_server, 1883);
  mqttclient.setCallback(callback);

}

void loop(void)
{
  LoRaNow.loop();
  server.handleClient();
  mqttloop();
}

void onMessage(uint8_t *buffer, size_t size)
{
  unsigned long id = LoRaNow.id();
  byte count = LoRaNow.count();

  Serial.print("Node Id: ");
  Serial.println(id, HEX);
  Serial.print("Count: ");
  Serial.println(count);
  Serial.print("Message: ");
  Serial.write(buffer, size);
  Serial.println();
  Serial.println();
  
   //此处通过mqtt发送信息。
   snprintf (msg, MSG_BUFFER_SIZE, "#%ld#%s", count,buffer);
   Serial.print("Publish message: ");
   Serial.println(msg);
   mqttclient.publish("C2TLOutTopic", msg);

  if (string.available() > 512)
  {
    while (string.available())
    {
      string.read();
    }
  }

  string.print("Node Id: ");
  string.println(id, HEX);
  string.print("Count: ");
  string.println(count);
  string.print("Message: ");
  string.write(buffer, size);
  string.println();
  string.println();

  // Send data to the node
  LoRaNow.clear();
  LoRaNow.print("LoRaNow Gateway Message ");
  LoRaNow.print(millis());
  LoRaNow.send();
}

void reconnect() {
  // Loop until we're reconnected
  while (!mqttclient.connected()) {
    Serial.print("Attempting MQTT connection...");
    // Create a random mqttclient ID
    String clientId = "ESP8266Client-";
    clientId += String(random(0xffff), HEX);
    // Attempt to connect
    if (mqttclient.connect(clientId.c_str())) {
      Serial.println("connected");
      // Once connected, publish an announcement...
      mqttclient.publish("C2TLOutTopic", "hello world");
      // ... and resubscribe
      mqttclient.subscribe("C2TLInTopic");
    } else {
      Serial.print("failed, rc=");
      Serial.print(mqttclient.state());
      Serial.println(" try again in 5 seconds");
      // Wait 5 seconds before retrying
      delay(5000);
    }
  }
}

void mqttloop() {

  if (!mqttclient.connected()) {
    reconnect();
  }
  mqttclient.loop();

//  unsigned long now = millis();
//  if (now - lastMsg > 2000) {
//    lastMsg = now;
//    ++value;
//    snprintf (msg, MSG_BUFFER_SIZE, "hello world #%ld", value);
//    Serial.print("Publish message: ");
//    Serial.println(msg);
//    mqttclient.publish("C2TLOutTopic", msg);
//  }
}
//求两者之间的相对距离
float dist(float latitude0,float latitude1,float longitude0,float longitude1 ){
distance=6371.0*(sin(latitude0)*sin(latitude1)+cos(latitude0)*cos(latitude1)*cos(longitude1-longitude0));return distance;}
//oled显示模块
U8GLIB_SSD1306_128X64 u8g(U8G_I2C_OPT_NONE|U8G_I2C_OPT_DEV_0);      // I2C / TWI
 void draw(void) {
// graphic commands to redraw the complete screen should be placed here
 u8g.setFont(u8g_font_unifont);
//u8g.setFont(u8g_font_osb21);
 u8g.drawStr( 0, 22, "Hello World!");
 }
 void setup(void) {
 }
 void loop(void) {
 // picture loop
 u8g.firstPage();
do {
 draw();
 } while( u8g.nextPage() );
 // rebuild the picture after some delay
 delay(50);
 }

   
## 5 性能指标

在性能评估时，主要从以下方面来评测：
### 1.手表的抗击打能力
### 2.手表的续航能力
### 3.手表定位功能在不同场景下的最大有效距离。
### 4.手表定位功能、温度湿度测量功能的精确程度。
  手表的抗击打能力：本智能手表外壳采用ABS材料制作，使用的ABS材料防火等级应该达到V0等级，ABS材料的抗击打性能比市面上很多PP材料制作的外壳好。同时70P的PVC，与人体接触的带子因为柔软程度高，不易变形和被破坏，所以不优先测试。
  测试时，用不同压力挤压手表，观测何时手表外壳ABS材料出现碎裂的情况。同时，利用能量和动量公式可以计算抗摔的高度等参数。
  19岁青年平均身高175.4cm，考虑到身高的正态分布，手表的抗摔高度应该达到175cm，以保证大多数情况下手表可以有较好的抗摔能力。手表的续航能力：本产品中，led模块的耗电量低，而esp32模块和gps模块由于存在通信功能，功耗较大，所以优先考虑这两者。Esp32的功耗是12mA，而gps模块的功耗是50mA。通过比对不同的纽扣二次电池，CR2477纽扣电池的容量达到了950mAh，可以支持设备工作15小时，可以满足白天使用、夜间充电的要求。
  在测试续航能力时，应该设置多组，一组在待机状态下（不收发消息）测试，一组在低频率收发消息状态下（每分钟gps和lora通信模块均收发消息2次，一组在高频率收发消息下（每秒钟gps和lora通信模块均收发消息1次），查看不同组的耗电速度，以此优化电池方案。
  手表定位功能在不同场景下的最大有效距离：lora模块的传输距离理论上可以达到5km。才测试的时候，考虑城市间的建筑物、乡村树木等大型障碍物的阻挡，以及在雾天等自然环境对传输距离的影响。应该尽可能保证在通常情况下，开放地带的传输距离最大为2km。
  在对手表的温湿度传感器测试时，应该保证温度在-10度到40摄氏度时，误差小于2摄氏度。可以通过在不同的环境下测试得出实际的传输距离。同时，修改程序中的参数，校准数值。在实测中，在温度为5摄氏度的情况下，可以达到要求，误差2摄氏度。







## 6  学习体会

  在21世纪的社会里，智能化将是一切生产和生活的必然趋势。我们正沿着信息高速公路迈向智能化社会的入口，而当前的信息革命是我们步入智能社会的必要前提。互联网、物联网和云计算等现代信息技术在社会生产各领域的广泛应用则加速了智能化化会的到来。智能社会的基本特征是生产智能化，生活智能化，具体表现就是智能机器大生产代替工业革命式的机器大生产，智能产品代替传统的工业产品，由此而引起一系列社会生活和狂会关系的深刻变生。人类社会将从工业文明时代跨入智能文明时代，在这个智能文明时代，智能机器不仅仅像传统机器那样是＂手＂的＂延伸＂，是＂体力＂的＂放大＂，而且还是＂脑＂的＂延伸＂，是＂智力＂的＂放大＂。智能社会将最大可能地实现物质财富的极大丰富，进一步解放人类的体力和脑为，使人类有更多的时间和精为来发展人类社会更高层次的文明。
    在智能化枉会中，智能产品将为人们的生活带来质的改变。而在诸多的智能产品中，首先走入人们视线的是那些最贴近人们生活的智能产品，如智能穿戴产品。智能穿戴产品是指能穿戴在身上或在概念上作为衣帽服饰的一部分而其本身又是具有一定智能功能的独立产品，智能穿戴产品是通过软件支持及数据交互、云端交互来实现生活智能化的一种现代化产品。即便我们现在的社会信息化程度相当发达，但离智能化社会还有一段距离。在从信息化向智能化社会迈进的过程中，首先走入人们生活的智能穿戴产品在智能化社会历史进程中起着启蒙和引导的作用。智能手环便是这诸多己经成型或即将成型的智能穿戴产品中的一种，智能手环在智能社会到来之前进入人们的生活中，开启人们对未来智能社会的想象空间，促进人们对智能化生产和生活的探索，穷实人们对智能社会的信也。因此，智能手环如同其它智能穿戴产品一样，在智能化社会的历史进程中起着启蒙和引导的作用。
  在这次的项目制作过程中，要感谢每个小组成员的辛勤付出，纵然作品没有达到想象的那样，但就过程而言我们收获到很多，去学习小组怎么去分工，怎么去合作，并体会到学习的快乐。





