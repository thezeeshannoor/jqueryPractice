------------------------------------------------ effects------------------------------------------------
->slideUp,slideDown slideToggle
->animate({property:value},speed,callback)
->stop()
->fadeIn,fadeOut fadeToggle
--------------------------------------------------------------------------------------------------------------------
-----------------------------------------------mouse event--------------------------------------------------------
->click: $("div").click(function(){})
->dblClick:$("div").dblclick(function(){})
->mouseleave:$("div").mouseleave(function(){});
->mouseenter:$("div").mouseenter(function(){});
--------------------------------------------------------------------------------------------------------------------
------------------------Get text using html(), text() and val() (val work with form input values)----------------
->html(): to get html elements and html text
->text(): to get only text
->val():work with form input values
--------------------------------------------------------------------------------------------------------------------
-------------------------------------------------Jquery Method----------------------------------------------------
->on(add multiple event handlers)
 $("p").on({
            click: function () { $(this).hide() },
            mouseenter: function () {
                $(this).css("color", "green");
            },
            mouseleave: function () {
                $(this).css("color", "black");
            },
        });
->show()
->hide()
->hover:$("div").hover()
->css(propertyname,value);//set css property
->attr $("#profile").attr({
                "href": "https://www.w3schools.com/jquery/jquery_dom_set.asp",
                "title": "W3 school"
            })
--------------------------------------------------------------------------------------------------------------------
-------------------------------------Jquery Add Html element-------------------------------------------------------
->append() add element at the end of the element
->prepend() add element start with in the selected element
->before() add element before the selected element
->after() add element  after the selected element
--------------------------------------------------------------------------------------------------------------------
----------------------------------------Jquery remove Html element-----------------------------------------------
->remove() remove the selected element with all the child nodes
->empty() remove all the child node but keep the selected element
->remove(".demo") //remove all elements that contain class="demo"
--------------------------------------------------------------------------------------------------------------------

-----------------------------------------jQuery Manipulating CSS---------------------------------------------------
jQuery has several methods for CSS manipulation. We will look at the following methods:

-->addClass() - Adds one or more classes to the selected elements
-->removeClass() - Removes one or more classes from the selected elements
-->toggleClass() - Toggles between adding/removing classes from the selected elements
-->css() - Sets or returns the style attribute


