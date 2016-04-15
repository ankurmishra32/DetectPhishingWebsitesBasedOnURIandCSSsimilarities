# Detect Phishing Websites attackes Based On URI and CSS similarities

In modern era of Internet, various organization/research groups are dealing with the advancement of security technology and security professionals are working hard to develop many mechanisms to fight against various cyber-crimes. It is difficult to breach these security systems by cyber-criminals. However, the weakest links in any organization and its legitimate users is the lack of cyber security awareness and lack of knowledge about the cyber-crimes, as security awareness among normal users is an often-overlooked factor. Organized cyber-criminals are putting significant efforts in research and development to create advanced tools and techniques to steal confidential information from the innocent (i.e. legitimate) users.
Today, phishing attack is one of the most common and serious threat over Internet which is used to fraud users and steal their personal information either by using spoofed emails or by using fake websites or both. To tackle the aforementioned securities issues we need to design an application for phishing detection. The application should cover a large area of phishing as per the latest trends report of phishing. Our design focuses on the phishing websites attacks. Phisher use spoofed emails and fraud websites to attack to victim.
However, we believe that the phishing websites are more dangerous and by covering phishing website attacks, we will also able to cover phishing email attacks. We present an intelligent hybrid solution (CUMP: CSS and URI Matching based Phishing Detection system) to defend against zero-day phishing attacks. The features used by the solution are hard to evaluate. The idea of our proposed approach is based on the concept of matching URI (Uniform Resource Identifier) and CSS (Cascading Style Style). Phisher use either spoofed mail or fraud websites with copycat design. As phisher always tries to mimic the URL pattern and visual design in hope that even experienced user will not be able to detect by visualization. Best way to mimic the visual appearance, phisher use same CSS style. Without using same CSS, it is very difficult to achieve same design. To defend against phishing websites attacks especially zero-day attacks, our proposed system (i.e. CUMP) uses the basic properties of any phishing attacks of URI and CSS matching. Our proposed solution is efficient, covers a wide range of websites phishing attacks and results in less false positive rate.


## Installation

Best way to use it to add it as a new project within Netbeans. You may have to configure libraries and handle file connectivity.

## Usage

We used various libraries to extract various information related to any website. Our solution in presnt situation work as follows:
1. Copy URI of website, which looks suspicious and paste it in solution's text area.
2. Click on the given button, it then start to check whether a website is really phish.
3. It first check, whether domain is in whitelist. If so, it will not check further and mark website as trusted.
4. If not, it try to findout the similarity score based on URI and CSS similarities of both suspicious and trusted pages.
5. Based on the threshold we calculated during the experiment, it decide whether page is phish.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

TODO: Write history

## Credits

TODO: Write credits

## License

 Copyright (c) June, 2014.
 
 E-Mail : ankurmishra32@gmail.com 

 Last modification by : Ankur Mishra 