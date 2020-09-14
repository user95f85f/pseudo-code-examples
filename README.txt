#!/usr/bin/pytech


$screen = read-in-screen();
edit(&$screen);
undef $screen;
exit 0;
#!/usr/bin/pytech


exec($self); #however it sees
$self = read-in($ENV{CONF_FILENAME}); #the configuration file gives everything
$self.exec();
#!/usr/bin/pytech



import * from everything.*;
import all-conf from all-possible-configuration.*;
exec(*);
return 400;


$the-file = "$HOME/Desktop/mycode.txt";
$human = sys.get-human();
$code = $human.think().extract-code();
$human.type($code, file=$the-file);
unset($code);
do-a-type-of-execute($the-file); #watch the fireworks
unset($the-file);

unset($human);
exit 0;
#!/usr/bin/pytech


exit 2^64;
exit 300billion%;
exit 400million;

import sys;

@a = get-list-of-urls(); //from an sqlite database
$b = fetch-all-data(@a); //with sockets
unset @a;
$c = create-report($b); #$c is a data-object
unset $b;
$date = Date.now.format('YYYY-MM-DD hh-mm-ss');
/*
auto-strip html, auto-wrap-to html, file-extension detect
*/
$file-txt-out = "$HOME/Desktop/myreport$date.txt";
$file-txt-conf-out = "$HOME/Desktop/myreport$date.txt.conf";
$file-html-out = "$HOME/Desktop/myreport$date.html";
file-put-contents($file-txt-out, $c);
file-put-contents($file-txt-conf-out, get-conf-out-data());
file-put-contents($file-html-out, $c);
unset $c;

Threads.multiThread(new Thread(){
/*** the .conf is only opened if it exists */
sys.ai.figure-out-and-execute-somehow($file-txt-out, $file-txt-conf-out)
});

exit 0;
#!/usr/bin/pytech

$game_location = sprintf("$ENV{HOME}/Game%03d", sys.rand(0, 999));
sys.mkdir($game_location);
$self.create-game().output($game_location).play();
exit 42;
#!/usr/bin/pytech

mkdir "$ENV{HOME}/Read"
&(**Internet)->aggregate-download()->download-all-files()->
sort-paragraphs()->put-most-interesting-read(
  to-read=>"$ENV{HOME}/Read/best.txt"
);
#!/usr/bin/pytech

mkdir("$ENV{HOME}/Games") || echo 'oh well already made.';
echo 'press ENTER to start the downloading and installing';
read(stdin);
go-onto-internet().get-best-video-games().install("$ENV{HOME}/Games/");
#!/usr/bin/pytech

go-onto-internet(search => '*').download-all().save(to=>"$ENV{HOME}/Downloads/");
exit 200;

mkdir("$ENV{HOME}/out") or die $!;
Internet.download-all().
play().read-into().
extract().save-all(
"$ENV{HOME}/out").
play().read().
output-conf('/etc/prog.conf')

Me.createInstance().
createThread().
manageProcess(0).
set_conf('me.conf').
go();

#!/usr/bin/pytech

$self.create-code("$ENV{HOME}/Code/out.py");
$self.think-deep();
$self.fflush();
exec("python3 $ENV{HOME}/Code/out.py");
unset $self;
exit 42;
#!/usr/bin/pytech


find-all-games-installed()->report-current-games()->msgbox.show();
$mind = read-mind();
play-best-game-rand($mind.select-games());
$self.play();
