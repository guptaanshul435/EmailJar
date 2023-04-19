# EmailJar


Now sending email is very easy in java. Simply folow below code.

public class MyApplication {
public static void main(String[] args) {
        String fromId="take from Id"
	String password="take two factorAuthentication password of formid"
	String subject="take your subject line"
	String body="take your body content"
	String[] bccIds= {"guptaanshul435@gmail.com"};
        String[] ccIds= {"guptaanshul435@gmail.com"};
	File[] files= {new File("C://Users//Dell//Pictures//dp_youdube.png"),new File("C://Users//Dell//Pictures//dp_youdube.png")};
	EmailDetails add =new EmailDetails();
	Email email=add.setToIds(res,add)
			.setFromId(fromId,add)
			.setPassword(password,add)
			.setSubject(subject,add)
			.setBody(body,add)
			.setBCCIds(bccIds[], add)
			.setCCIds(ccIds[], add)
			.setAttaichFiles(files[],add)
			.buildEmail();
	email.sendEmail();	
   }	
}
