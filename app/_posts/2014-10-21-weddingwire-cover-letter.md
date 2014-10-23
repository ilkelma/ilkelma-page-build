---
layout: coverletter
title:  "To Weddingwire!"
date:   2014-10-21 14:12:55
categories: coverletters
---
# WeddingWire team:

Greetings, I'm Andy Knight and I'm a full stack web developer (<i class="fa fa-desktop"></i> <i class="fa fa-exchange"></i> <i class="fa fa-cogs"></i> <i class="fa fa-exchange"></i> <i class="fa fa-database"></i>). I have worked primarily across the JVM stack using statically typed Java, dynamic JVM languages like Groovy and even some of the newer type-safe functional languages like Scala. I have built applications across all ends of the stack from thick client Angular.js, HTML and CSS with "stateless" RESTful APIs, to session/servlet based SpringMVC applications driven by jQuery front-ends. I've even written a good bit of PL/SQL as backend code in some applications.

I consider myself a polyglot programmer adept at learning new languages and frameworks. I have dabbled in languages such as Ruby and frameworks like Rails, as well as Fabric scripts written in Python. More germane to this position is my extensive use of Groovy which is a dynamic language with more than a passing resemblance to Ruby. For instance, you can easily spot the similarities in the example below:

<div class="row">
  <div class="col-md-6">
    <div class="lang-icon"><a href="http://rubyfiddle.com/riddles/95a34" title="Run me on ruby fiddle!"><i class="devicons devicons-ruby text-danger"></i> <small>Ruby</small></a></div>
{% highlight ruby %}
dynamicLanguages = ["Python", "Ruby", "Groovy"]
def playWithLanguages(languages)
  languages.each do |lang|
    puts "#{lang} supports string interpolation"
    puts "and everything is an object".reverse
  end
end
playWithLanguages(dynamicLanguages)
{% endhighlight %}
  </div>
  <div class="col-md-6">
    <div class="lang-icon"><a href="http://groovyconsole.appspot.com/script/5632457692938240"><i class="devicons devicons-groovy text-primary" title="Run me in the groovy web console (click edit in console, execute script then check the output tab)!"></i> <small>Groovy</small></a></div>
{% highlight groovy %}
def dynamicLanguages = ["Python", "Ruby", "Groovy"]
def playWithLanguages(languages) {
  languages.each { lang ->
    println "${lang} supports string interpolation"
    println "and everything is an object".reverse()
  }
}
playWithLanguages(dynamicLanguages)
{% endhighlight %}
  </div>
</div>

More complex examples diverge, but the primary concepts at the heart of Groovy are very similar to those of Ruby, both in philosophy and implementation. I am also familiar with a variety of Rails concepts managing and versioning dependencies, which I have used extensively through [Bower<i class="devicons devicons-bower"></i>][bower] (which even betrays its conceptual origins when the driving file's filenames are examined: Gemfile and Bowerfile). Another Rails-like practice is my use of [grunt<i class="devicons devicons-grunt"></i>][grunt], which is comparable to the asset pipeline in rails. Both Rails and grunt perform similar tasks in order to keep front-end asset load times speedy, though grunt is also used to perform tasks usually done with rake in Rails.

I believe I have the skills, passion, dedication and aptitude to learn and excel in any web environment including Rails. I am a quick and agile learner as demonstrated by my ability to teach myself (within a couple months) how to build and contribute to production code in a SpringMVC/Hibernate application from a very basic knowledge of applet Java. I also have a passion for DevOps tasks such as provisioning servers and setting up repeatable build and testing processes as part of a continuous integration/continuous delivery strategy. Automation is one of my passions as well and I enjoy building tools and scripts to streamline developer workflows in order to enhance productivity.

Thank you for taking the time to read this and I look forward to talking to you more about this position,

![Signed Andrew M. Knight][amksig]

[bower]: http://www.bower.io
[grunt]: http://gruntjs.com/
[amksig]: {{ site.url }}/img/amksign.png
