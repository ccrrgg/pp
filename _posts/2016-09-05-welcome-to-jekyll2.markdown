---
layout: post
title:  "Welcome tasfa"
date:   2016-09-05 09:44:40 +0000
categories: jekyll update
---
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:


<!-- pp.html -->
<!-- ffactura de la luz -->







<pre>
introdcir los datos como fomulario dela pagina
calcular los dias como diferencia de fechas




<script type="text/javascript">


  HastaFecha = '04/10/2015'
  DesdeFecha = '11/08/2015'

  LecturaAnterior = 135783
  LecturaActual = 135963
  dias = 444
  document.writeln(' Factura de luz desde ', DesdeFecha, ' hasta ', HastaFecha, ' ***', dias, ' dias*** ')
  document.writeln('\n')
  Potencia = 3.3
  TerminoPotencia = 0.115383
  fppc = Potencia * TerminoPotencia * dias
  document.writeln(' >>>>>>>>>>>>>>>>>    ', fppc, ' eur por ', Potencia, ' kW contratados');
  document.writeln('\n')
  TerminoEnergia = 0.123512
  fpec = (LecturaActual - LecturaAnterior) * TerminoEnergia
  document.writeln('  >>>>>>>>>>>>>>>>>    ', fpec, ' eur por ', LecturaActual - LecturaAnterior, ' kwh consumidos ')
  total=(fppc+fpec)*1.21
  document.writeln('>>>>>>>>>>>>>>>>>        Total ',total,' eur (IVA incl.) ');

  //document.writeln('Importe Peaje Acceso = ',ImportePeajeAccesoE,' eur')                factura=fppc+fpec      //document.writeln('    Subtotal ',factura,' eur')          //otros conceptos      dto=-0.1*Potencia*TerminoPotencia*dias            //document.writeln(dto)      ie=(factura+dto)*1.05113*4.864/100      //document.writeln(ie)            aemyc=0.0196777*dias      //document.writeln(aemyc)      otros=aemyc+ie+dto      document.writeln('    ',otros,' eur de otros conceptos');          document.writeln()      total=(fppc+fpec+otros)*1.21      document.writeln('        Total ',total,' eur (IVA incl.) ');


</script>



{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
