ERB-Sublime-Snippets
====================

A collection of [Sublime Text](http://www.sublimetext.com/) snippets useful for writing [ERB](http://ruby-doc.org/stdlib-1.9.3/libdoc/erb/rdoc/ERB.html)

##Installation

These snippets can now be installed via [Sublime Package Control](http://wbond.net/sublime_packages/package_control). If you do not use package control, simply checkout the source code into Sublime Text's packages directory. The location is system specific:

### For OSX

    $ cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages
    $ git clone https://github.com/ivorpad/ERB-Sublime-Snippets.git ERB_Snippets


##Snippets and Bindings

<table>
  <tr>
    <th>Snippet</th>
    <th>Tab Trigger</th>
    <th>Output</th>
  </tr>
  <tr>
    <td>ERB tags</td>
    <td>__-__</td>
    <td>`<%  %>`</td>
  </tr>
  <tr>
    <td>print ERB tags</td>
    <td>__=__</td>
    <td>`<%=  %>`</td>
  </tr>
  <tr>
    <td>print ERB comment</td>
    <td>__//__</td>
    <td>`<%#  %>`</td>
  </tr>
  <tr>
    <td>`if` block</td>
    <td>__if__</td>
    <td>`<% if  %>...<% end %>`</td>
  </tr>
  <tr>
    <td>`if` / `else` block</td>
    <td>__ife__</td>
    <td>`<% if  %>...<% else %>...<% end %>`</td>
  </tr>
  <tr>
    <td>`else` tag</td>
    <td>__else__</td>
    <td>`<% else %>`</td>
  </tr>
  <tr>
    <td>`elsif` tag</td>
    <td>__elsif__</td>
    <td>`<% elsif %>`</td>
  </tr>
  <tr>
    <td>`unless` block</td>
    <td>__unless__</td>
    <td>`<% unless  %>...<% end %>`</td>
  </tr>
  <tr>
    <td>`end` block</td>
    <td>__end__</td>
    <td>`<% end %>`</td>
  </tr>
  <tr>
    <td>`submit_tag` helper</td>
    <td>__st__</td>
    <td>`<%= submit_tag ..., ... %>`</td>
  </tr>
  <tr>
    <td>`text_field_tag` helper</td>
    <td>__tft__</td>
    <td>`<%= text_field_tag ..., ... %>`</td>
  </tr>
  <tr>
    <td>`password_field_tag` helper</td>
    <td>__pft__</td>
    <td>`<%= password_field_tag ..., ... %>`</td>
  </tr>
  <tr>
    <td>`label_tag` helper</td>
    <td>__lblt__</td>
    <td>`<%= label_tag ..., ... %>`</td>
  </tr>
  <tr>
    <td>`link_to` helper</td>
    <td>__lt__</td>
    <td>`<%= link_to ..., ... %>`</td>
  </tr>
  <tr>
    <td>`each` helper</td>
    <td>__each__</td>
    <td>`<% @things.each do |thing| %> ... <% end %>`</td>
  </tr>
  <tr>
    <td>`form_for` helper</td>
    <td>__ff__</td>
    <td>`<%= form_for(@ ) do |f| %> ... <% end %>`</td>
  </tr>
  <tr>
    <td>`t()` helper</td>
    <td>__t__</td>
    <td>`<%= t('@') %>`</td>
  </tr>
<table>

## Just changed a couple of triggers and I prefer instead on the regular `er`, `pc`, `pe`

##License

Released under [WTFPL, Version 2](https://raw.github.com/matthewrobertson/ERB-Sublime-Snippets/master/LICENSE.txt)
