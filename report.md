
#前言#
##1.1 作业背景##
&nbsp;&nbsp;&nbsp;&nbsp;本文根据《管理信息系统》课程要求而做。  
&nbsp;&nbsp;&nbsp;&nbsp;课程要求如下：  
  
&nbsp;&nbsp;&nbsp;&nbsp;用管理信息系统开发工具（例如VisualBasic、VisualFoxpro、Access、PowerBuilder、Delphi等）开发一个实用的中小型管理信息系统。  
  1.   根据课程设计时间选择适当规模大小的设计课题。  
  2.   根据合理的进度安排，按照系统开发的流程及方法，踏实地开展课程设计活动。  
  3.   课程设计过程中，根据选题的具体需求，在开发各环节中撰写相关的技术文档，最后提交详细的课程设计报告，至少包括系统可行性分析报告、系统分析报告、系统设计报告三个主要部分。  
  4.   开发出可以运行的管理信息系统，通过上机检查。  
  
##1.2 选题说明##
&nbsp;&nbsp;&nbsp;&nbsp;学生会，是大学身在高校校园里的一个重要的学习、生活、交往的环境，学生会管理是高校师生共同的基础管理工作，学生会管理信息系统对于一个高校来说是必不可少的组成部分。学生会包含了大一到大三各个年级的学生以及指导老师，他们有各自的职务。随着学生会人数的增多，学校对学生会管理效率要求的提高，全人工管理已无法满足需求，针对于此我们设计一套学生会管理信息系统。

**(1)基本思路**    
&nbsp;&nbsp;&nbsp;&nbsp;学生会管理信息系统，是以高校管理方式设计的一种实用性管理系统。本系统最大的特点是通用行、简单操作性强。目前我校的学生面对学校发展的实际状况，通过实地调查，结合日常生活经验，我们设计了一套学生会管理信息系统，采用Java 、Eclipse、SQL作为开发工具开发。  
**(2)作业目标**    
&nbsp;&nbsp;&nbsp;&nbsp;采用计算机化管理，由过去的人工方式转变为计算机方式，查找方便，安排合理，可靠性高。团委学生会信息管理系统主要包括学生干部信息管理系统、财务管理系统、日常事务管理系统、文件管理系统等，可以更快地了解到每个学生在哪个部门，其指导教师是谁，日常业务流程、活动宣传等使学生会总体管理效率更高，使操作者能够方便的使用，尽量做到人性化设计为，节省相当大的人力物力财力。  

##1.3 工作业绩##
待添加  

#第二章 前期调研#
##2.1 管理学院团委学生会管理现状##

###2.1.1  学生干部信息管理###
&nbsp;&nbsp;&nbsp;&nbsp;学生从进入学生会开始，就会录入并不断更新信息，目前，部员、副部、部长、主席，他们各自的信息只有小部分范围内得知，如若有在整个学生会想了解他们的学生，则没有在线的渠道。老师如果想查看学生干部的信息也便对他们就行评定考核，也需要翻看纸质的档案，很不方便。    
###2.1.2  财务管理###
&nbsp;&nbsp;&nbsp;&nbsp;财务管理包括财产和物品管理。目前管理学院的财产管理主要是通过学生干部列出需购买的产品或服务的清单，然后到老师办公室审批盖章，然后暂借资金，学生干部采购完成后核对清单，清算账目，再多退少补。整个过程非常繁琐，对学生老师都不利。物品管理方面，每次各个部门要使用物资时，都是手工的登记，用完并将物品归还后，在在登记册上签字。全程需要值班人员。  
###2.1.3  日常事务管理###
&nbsp;&nbsp;&nbsp;&nbsp;日常事务管理包括各部门提交的工作计划、活动计划的审核与安排、活动的筹划、各项活动的人员的合理调度安排，各项活动成功的举办的基本物质保证。目前来看，管理学院团委学生会六大中心对各项日常事务的安排联系的很紧密，但也很繁琐，缺少统筹者。  
###2.1.4  文件管理###
&nbsp;&nbsp;&nbsp;&nbsp;团委学生会不是每个部门开展了活动后都能做到及时存档，即使有存档，随着时间的推进也不能实时更新，有碍于各项工作的顺利开展。  

##2.2  问题分析##
&nbsp;&nbsp;&nbsp;&nbsp;上述学生会管理现状说明了一个问题，就是目前我们缺少一个专业、高效、便捷的在线管理平台。导致学生会平时工作的开展秩序混乱，无章可循。  
##2.3  解决方案##
&nbsp;&nbsp;&nbsp;&nbsp;开发本系统有助于对学院团委学生会进行高效、集中的管理。通过对团委学生会所需的信息管理，把主管老师和各部长从繁琐的数据计算处理中解脱出来，使其更多的精力从事各种活动的研究实施，活动计划的制定执行和活动质量的监督检查，从而全面提高团委学生会的总体运作能力。 

#第三章 系统分析#
##3.1  可行性分析##
###3.1.1  技术可行性分析###
&nbsp;&nbsp;&nbsp;&nbsp;目前校园网已在学校良好运行，校园网络已全面覆盖整个学校。在硬件方面，我校有大批高性能的计算机和相应的配套设施能够满足相关要求。在软件方面，学校可以提供正版的操作系统，有现成的数据库管理系统，我们也可以将此系统与学校的其他管理系统结合在一起，达到综合管理的目的。同时我们开发学生会管理信息系统的条件也相对成熟，有一系列的现成的相关软件可以参考。学院大部分人员对计算机技术有一定的了解，也有一定的计算机操作能力，实施新系统后只需经过简单的培训即可。学校原有的计算机管理和维护工作由综合管理部门下属的微机室负责，有两名以上的具有一定软硬件能力的计算机专业人员。  
###3.1.2  经济可行性分析###
&nbsp;&nbsp;&nbsp;&nbsp;费用主要包括设备购置费、开发费用、管理和维护费用。设备费用包括计算机硬件以及相关的配套设施，这是主要的费用来源。开发费用系统开发的费用及其他相关费用，由于开发的条件已相对成熟，此项费用占比相对较少。管理和维护费用包括工作人员的工资和其他系统运行相关的费用。我们可以在每年特定的时间对新入职的学生干部进行相关的培训，已达到使用此系统的目的，从而节省额外人员费用的开支。  
###3.1.3  社会可行性分析###
**（1）社会法律政策可行性：**   
&nbsp;&nbsp;&nbsp;&nbsp;该系统的开发不会侵犯他人、集体和国家的利益，也不会违反国家的政策和法律，因此在法律方面是可行的。所有技术资料都由提出方保管。  
**（2）社会公共环境可行性：**    
&nbsp;&nbsp;&nbsp;&nbsp;建立先进的信息管理系统是实现高等教育现代化的必由之路。本次开发旨在进一步完善学院团委学生会的管理，实现真正的服务大家。学院的团委学生会管理存在不足，局限性很大，开发本系统能为学院带来高效的管理。运用，则是推进高校团委学生会管理的重要举措之一。提高学院团委学生会管理，不但可以为团委学生会内部的主席团、各部门的部长对整个团委学生会的管理的完善，而且可以为干部以及其他干部人员及时的查询资料，比如，随时更新各系的活动动态以便各系及时的了解他们的资料，同时也可以为其他同学提供更加方便的了解学院各时间段的活动动态。为团委的工作带来更大的便捷。  
**（3）用户使用可行性：**          
&nbsp;&nbsp;&nbsp;&nbsp;开发该系统充分考虑了用户操作方便、处理流程、人员素质等多方面的因素，因此能够满足用户的需求，所以用户使用方面也是可行的。使用本软件人员要求有一定计算机基础。操作人员需要重新上机培训，可以避免大量开发费用。
通过以上的分析，可以确定本系统开发在社会环境因素方面上是完全可行的通过以上的分析，可以确定本系统开发在社会环境因素方面上是完全可行的。  

##3.2  组织结构分析##


###3.2.1  团委学生会结构分析###

![组织结构图](http://ww2.sinaimg.cn/mw1024/ec2e3c8bgw1exlx8uzvisj20fe08o75q.jpg) 

###3.2.2  各中心职能简单说明###
**团委：**分管组织部、宣教部、科技协会、实践部等四个部门，团结带领青年学生树立自力更生，艰苦创业，自强不息的奋斗精神。积极推动社会主义物质文明、政治文明和精神文明建设。  
**学生会：**分管文艺部、体育部、生活部、外联部、学习部等五个部门，是一个学生自我管理自我服务的群众性组织，是学校联系学生的纽带和桥梁。  
**传媒中心：**分管春花采编部、宣传设计部、新媒体、记者站、秘书处等五个部门，主要负责学院的活动宣传、文化传播和形象设计等工作。    
**公益服务发展中心：**分管青年志愿者协会、乐奉服务分队、爱心基金会等三个部门，主要负责学院的公益服务活动。将一群具有爱心的人聚在一起，通过举办各种公益活动去感染所有学生。  
**社团中心：**分管二十余个社团，是广大具有特殊爱好学生聚集地。相比于学生会其他部门，社团中心没有那么严肃，这里更多的是学生自我发挥的天地。  

###3.2.3  各部门工作合作分析###
&nbsp;&nbsp;&nbsp;&nbsp;团委学生会分为六个中心，各个中心在紧密合作的前提下各施其职。团委和学生会下的部门统筹整个团委学生会的工作，其它中心分管不同的模块。由于不少的同学都不止参加一个部门，所以各个部门的间的协作沟通显得尤为重要，因此所有都涉及到四个子系统。  

##3.3  功能结构分析##
###3.3.1  各系统功能概述###
**学生干部信息管理系统**  
&nbsp;&nbsp;&nbsp;&nbsp;学生会干部信息管理系统主要完成干部信息的查询与更新，针对他们的奖惩情况，从而实现对学生会干部信息的科学管理。  
**财务管理系统**  
&nbsp;&nbsp;&nbsp;&nbsp;财务管理信息系统包括财务和物品的管理，完成对财产物品信息的查询与更新，如举办活动所需的资金申请、物品使用的登记、物品借还的登记等，从而实现学生会财务的信息化管理。  	
**日常事务管理系统**  
&nbsp;&nbsp;&nbsp;&nbsp;日常事物管理系统实现对学生会日常工作的管理，完成日常事物的查询与更新，从而实现以下职能：包括各部门提交的工作计划、活动计划的审核与安排、活动的筹划、各项活动的人员合理的调度与安排，确保各项活动成功地举办，更有利于学生会各项日常工作的顺利开展。  
**文件管理系统**  
&nbsp;&nbsp;&nbsp;&nbsp;文件管理系统完成对学生会所有存档文件的查询与更新，实现对学生会日常工作文件的科学化管理，从而确保各项工作的开展有章可寻，使学生会的工作更富有调理化，避免一些重复文件的制定，造成资源浪费。  

###3.3.2  功能结构图###



![功能结构图](http://ww2.sinaimg.cn/mw1024/ec2e3c8bgw1exlx8ypam7j20fe0bqdhw.jpg)  
###3.3.3 用例分析###
![](http://ww4.sinaimg.cn/mw690/ec2e3c8bgw1extulb2ptkj20ff0co771.jpg)

##3.4  业务流程分析##
###3.4.1  人员管理系统业务流程图###


![人员管理系统](http://ww2.sinaimg.cn/mw690/ec2e3c8bgw1exlxt800g2j20el0eg751.jpg)

###3.4.2  文件管理系统业务流程图###


![文件管理系统](http://ww2.sinaimg.cn/mw690/ec2e3c8bgw1exlxt7mbzvj20et0a6weu.jpg)

###3.4.3财务管理系统业务流程图###

![财务管理系统](http://ww1.sinaimg.cn/mw690/ec2e3c8bgw1exlxt8lkbcj20fe0e00tn.jpg) 

###3.4.4日常事务业务流程图###


![日常事务](http://ww2.sinaimg.cn/mw690/ec2e3c8bgw1exlxt8ne3pj20fe0bwwfd.jpg)


##3.5  系统逻辑模型##
###3.5.1  数据建模###
![](http://ww1.sinaimg.cn/mw690/ec2e3c8bgw1exooqjrf9xj20j805gt8t.jpg)
![](http://ww1.sinaimg.cn/mw690/ec2e3c8bgw1exooqk8r8bj20n40ddwfi.jpg)
![](http://ww3.sinaimg.cn/mw690/ec2e3c8bgw1exooqkuqp0j20pg0f675r.jpg)
![](http://ww4.sinaimg.cn/mw690/ec2e3c8bgw1exooqlggb1j20if0e8jsm.jpg)

###3.5.2  过程建模###
![](http://ww3.sinaimg.cn/mw690/ec2e3c8bgw1exooqm8s0qj20kw0f140z.jpg)
![](http://ww2.sinaimg.cn/mw690/ec2e3c8bgw1exooqmqjr0j20jq08tq3t.jpg)
###3.5.3  Axure原型设计###


#第四章 系统设计#
##4.1 前台##
![](http://ww4.sinaimg.cn/mw690/ec2e3c8bgw1ey374gpl54j211t0ilaan.jpg)
![](http://ww2.sinaimg.cn/mw690/ec2e3c8bgw1ey374hg0iaj20v80jeglu.jpg)
![](http://ww1.sinaimg.cn/mw690/ec2e3c8bgw1ey374gz5zij20hf0a4glf.jpg)
##4.1 后台##
###4.1.1 javabeen###
  以学生类为例
  
					private String StuNo;
					private String StuName;
					private String StuSex;
					private String StuMajor;
					private String StuGrade;
					private String StuPhoneNo;
					public String getStuNo() {
						return StuNo;
					}
					public void setStuNo(String stuNo) {
						StuNo = stuNo;
					}
					public String getStuName() {
						return StuName;
					}
					public void setStuName(String stuName) {
						StuName = stuName;
					}
					public String getStuSex() {
						return StuSex;
					}
					public void setStuSex(String stuSex) {
						StuSex = stuSex;
					}
					public String getStuMajor() {
						return StuMajor;
					}
					public void setStuMajor(String stuMajor) {
						StuMajor = stuMajor;
					}
					public String getStuGrade() {
						return StuGrade;
					}
					public void setStuGrade(String stuGrade) {
						StuGrade = stuGrade;
					}
					public String getStuPhoneNo() {
						return StuPhoneNo;
					}
					public void setStuPhoneNo(String stuPhoneNo) {
						StuPhoneNo = stuPhoneNo;
					}
				}
##4.1.2 方法##
 以物品的方法为例
 				
				import eb.java.studentunion.DbUtil;
				import eb.java.studentunion.entity.Goods;
				
				public class GoodsDal {
				
					public static boolean addGoods(int GoodsNo,String GoodsName, String GoodsBuyTime,
							float GoodsPrice, int TotalNumber,int AvailableNumber) 
					//添加类物品
					{
						int i = 0;
						Connection connection = DbUtil.getConnection();
						PreparedStatement pstat;
						try {
							pstat = connection
									.prepareStatement("insert into Goods(GoodsNo,GoodsName,GoodsBuyTime
									,GoodsPrice,TotalNumber,AvailableNumber) values(?,?,?,?,?,?)");
							pstat.setInt(1, GoodsNo);
							pstat.setString(2, GoodsName);
							pstat.setString(3, GoodsBuyTime);
							pstat.setFloat(4, GoodsPrice);
							pstat.setInt(5,TotalNumber);
							pstat.setInt(6, AvailableNumber);
							i = pstat.executeUpdate();
						} catch (SQLException e) {
							// TODO Auto-generated catch block
							e.printStackTrace();
						}
						return i > 0;
					}
				
					
				
					public static boolean updateGoods(int GoodsNo,String GoodsName, String GoodsBuyTime,
							float GoodsPrice, int TotalNumber,int AvailableNumber) 
					//更新物品表
					{
						int i = 0;
						Connection connection = DbUtil.getConnection();
						PreparedStatement pstat;
						try {
							pstat = connection
									.prepareStatement("update Goods set GoodsName=? ,GoodsBuyTime=?,GoodsPrice=?,TotalNumber=?,AvailableNumber=? where GoodsNo=?");
							pstat.setString(1, GoodsName);
							pstat.setString(2, GoodsBuyTime);
							pstat.setFloat(3, GoodsPrice);
							pstat.setInt(4, TotalNumber);
							pstat.setInt(5, AvailableNumber);
							pstat.setInt(6, GoodsNo);
							i = pstat.executeUpdate();
						} catch (SQLException e) {
							// TODO Auto-generated catch block
							e.printStackTrace();
						}
						return i > 0;
					}
				
					public static List<Goods> getAllGoods() //获取所有物品
					{
						List<Goods> allGoods=new ArrayList<Goods>();
						ResultSet rs = null;
						Connection connection = DbUtil.getConnection();
						PreparedStatement pstat;
						try {
								pstat = connection
										.prepareStatement("select * from Goods");
							rs = pstat.executeQuery();
							if(rs!=null){
								while(rs.next())
								//赋值
								{
									Goods goods=new Goods();
									goods.setGoodsName(rs.getString("GoodsName"));
									goods.setGoodsNo(rs.getInt("GoodsNo"));
									goods.setGoodsBuyTime(rs.getString("GoodsBuyTime"));
									goods.setGoodsPrice(rs.getFloat("GoodsPrice"));
									goods.setTotalNumber(rs.getInt("TotalNumber"));
									goods.setAvailableNumber(rs.getInt("AvailableNumber"));									
									allGoods.add(goods);
								}
							}
							rs.close();
							pstat.close();
							connection.close();
						} catch (SQLException e) {
							// TODO Auto-generated catch block
							e.printStackTrace();
						}
						return allGoods;
					}
					public static List<Goods> getByGoodsSn() //查询物品
					{
						List<Goods> allGoods=new ArrayList<Goods>();
						Goods goods=new Goods();
						ResultSet rs = null;
						Connection connection = DbUtil.getConnection();
						PreparedStatement pstat;
						try {
								pstat = connection
										.prepareStatement("select * from Goods where GoodsSn='JYDQ_DJD_SD_1'");
							rs = pstat.executeQuery();
							if(rs!=null){
								while(rs.next())
								//赋值
								{					
									goods.setGoodsName(rs.getString("GoodsName"));
									goods.setGoodsNo(rs.getInt("GoodsNo"));
									goods.setGoodsBuyTime(rs.getString("GoodsBuyTime"));
									goods.setGoodsPrice(rs.getFloat("GoodsPrice"));
									goods.setTotalNumber(rs.getInt("TotalNumber"));
									goods.setAvailableNumber(rs.getInt("AvailableNumber"));									
									allGoods.add(goods);
								}
							}
							rs.close();
							pstat.close();
							connection.close();
						} catch (SQLException e) {
							// TODO Auto-generated catch block
							e.printStackTrace();
						}
						return allGoods;
					}							
				}


				 



















  







