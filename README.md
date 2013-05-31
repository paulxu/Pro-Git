Pro-Git
=======

note for the book " Pro Git"

http://git-scm.com/book

git init  

git pull git@github.com:paulxu/Pro-Git.git

-----
Integration with Komodo IDE, version 8.0.2, build 78971

file > source code control > checkout

git
https://github.com/paulxu/Pro-Git.git
/tmp

file > source code control > commit changes (local commit)

file > source code control > push (update github)

~/.netrc

machine github.com

     login <user>
    
     password <password>
    
-----
Note:

https://help.github.com/articles/github-flavored-markdown





What about some code **in** a list? That's insane, right?

1. In Ruby you can map like this:

        ['a', 'b'].map { |x| x.uppercase }

2. In Rails, you can do a shortcut:

        ['a', 'b'].map(&:uppercase)

Some people seem to like definition lists

<dl>
  <dt>Lower cost</dt>
  <dd>The new version of this product costs significantly less than the previous one!</dd>
  <dt>Easier to use</dt>
  <dd>We've changed the product so that it's much easier to use!</dd>
</dl>

I am a robot
------------

Maybe you want to print `robot` to the console 1000 times. Why not?

    def robot_invasion
      puts("robot " * 1000)
    end

You see, that was formatted as code because it's been indented by four spaces.

How about we throw some angle braces and ampersands in there?

    <div class="footer">
        &copy; 2004 Foo Corporation
    </div>

Set in stone
------------

Preformatted blocks are useful for ASCII art:

<pre>
             ,-.
    , ,-. ,-.
   / \ ( )-( )
   \ | ,.>-( )-<
    \|,' ( )-( )
     Y ___`-' `-'
     |/__/ `-'
     |
     |
     | -hrr-
  ___|_____________
</pre>

Playing the blame game
----------------------

If you need to blame someone, the best way to do so is by quoting them:

> I, at any rate, am convinced that He does not throw dice.

Or perhaps someone a little less eloquent:

> I wish you'd have given me this written question ahead of time so I
> could plan for it... I'm sure something will pop into my head here in
> the midst of this press conference, with all the pressure of trying to
> come up with answer, but it hadn't yet...
>
> I don't want to sound like
> I have made no mistakes. I'm confident I have. I just haven't - you
> just put me under the spot here, and maybe I'm not as quick on my feet
> as I should be in coming up with one.

Table for two
-------------

<table>
  <tr>
    <th>ID</th><th>Name</th><th>Rank</th>
  </tr>
  <tr>
    <td>1</td><td>Tom Preston-Werner</td><td>Awesome</td>
  </tr>
  <tr>
    <td>2</td><td>Albert Einstein</td><td>Nearly as awesome</td>
  </tr>
</table>

Crazy linking action
--------------------

I get 10 times more traffic from [Google] [1] than from
[Yahoo] [2] or [MSN] [3].

  [1]: http://google.com/ "Google"
  [2]: http://search.yahoo.com/ "Yahoo Search"
  [3]: http://search.msn.com/ "MSN Search"