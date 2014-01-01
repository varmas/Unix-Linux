Level 0,1

<pre><code>ssh bandit.labs.overthewire.org -l bandit0
cat ~/readme
</code></pre>

Level 2

<pre><code>cat /home/bandit1/-
</code></pre>

Lesson I learned : Absolute Path or relative path needed for unix commands on paths/filenames starting with '-' 

Level 3

<pre><code>cat spaces\ in\ this\ filename
</code></pre>

Level 4

<pre><code>ls -a inhere/
cat inhere/.hidden
</code></pre>

Level 5

<pre><code>grep . inhere/*
or
tail inhere/*
</code></pre>

Lesson I learned : More standard practice to find the file types is <code>file inhere/*</code>

Level 6

<pre><code>find -perm -g-x -size 1033c
</code></pre>

Level 7

<pre><code>cd /
find -user bandit7 -group bandit6 -size 33c
to get rid of the Permission denied messages do this instead:
find -user bandit7 -group bandit6 -size 33c 2>/dev/null
</code></pre>

Lesson I learned : dev/null and stderr redirection

Notes : 0 stdin, 1 stdout, 2 stderr

Level 8

<pre><code>grep millionth data.txt
</code></pre>

Level 9

<pre><code>cat data.txt | sort | uniq -u
</code></pre>

Level 10

<pre><code>strings data.txt | grep "^=.*"
</pre></code>

Level 11

<pre><code></pre></code>
