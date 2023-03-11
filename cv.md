<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Markdown-cv</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <h1>Curriculum Vitae</h1>
    <main>
        <div class="div_1">
            <img src="foto_k.jpg" alt="avatar-foto" width='160' heigth='200'>
            <ul class="ul_1">
                <li class="size li_1">
                    Name: <b>Viachaslau</b><br>
                    Last name: <b>Kudaka</b><br>
                </li>
                <hr>
                <li><b class="size">Contacts:</b><br>
                    Email: <b>slavakudaka@gmail.com</b><br>
                    Phone :<b>+375336696160, +393335431282</b><br>
                </li>
                <hr>
                <li><b class="size">Locatione:</b><br>
                    <b>Belarus</b><br>
                    <b>Italy</b><br>
                </li>
                <hr>
            </ul>
        </div>
        <br>
        <div>

            <span><b>My Experience</b></span>
            <p>
                For 4 eyars worked as Communication technicians installer for OpenFiber company through
                EDSinfrastruttureSPA,
                maintain, testing and repair wiring or cable networks,creating Fiber networks.
                For 2 years worked as industrial electrical technician.
                For 2 ears for my own worked as technician configuring, repair and installing: cctv,wifi,networks,
                systems
            </p>
            <hr>
            <span><b>About Me</b></span>
            <p>
                Always want to learn new things and develop my skills to another level,
                for now i decided to try myself to code .
                I have tried Python,and i liked it.Now i want to try JS with RSscool
            </p>
            <hr>
            <span><b>Skills</b></span>
            <p>
            <ul>
                <li><b>HTML</b> (Basic)</li>
                <li><b>CSS</b> (Basic)</li>
                <li><b>Python</b></li>
                <li><b>Framework Django</b></li>
                <li><b>IDE: PyCharm, VScode</b></li>
                <li><b>configuring network device</b></li>
                <li><b>Python project on github <a
                            href="https://github.com/slavak9/python-test-project">https://github.com/slavak9/python-test-project</a>
                    </b></li>
            </ul>
            </p>
            <hr>
            <span><b>Aducation</b></span>
            <p>Has ended professional school</p>
            <hr>
            <span><b>Courses</b></span>
            <p>
            <ul>
                <li><b>INTERCONNECTING CISCO NETWORKING DEVICES PART 1(ICND1) – TRN-ICND1-2.0 </b>
                    school
                    <a href="https://training-microtest.ru/">https://training-microtest.ru/</a>
                </li>
                <li><b>INTERCONNECTING CISCO NETWORKING DEVICES PART 2 (ICND2) – TRN-ICND2-2.0 </b>
                    <a href="https://training-microtest.ru/">https://training-microtest.ru/</a>
                </li>
                <li><b>INTERCONNECTING CISCO NETWORKING DEVICES PART 1 (100-105)</b> (Have studied by myself)</li>
                <li><b>Fiber optic </b><a href="https://optel.ru/">https://optel.ru/</a></li>
                <li><b>Basic web technologies </b><a href="https://www.it-academy.by/">https://www.it-academy.by/</a>
                </li>
                <li><b>Python developer </b><a href="https://www.it-academy.by/">https://www.it-academy.by/</a></li>
            </ul>
            </p>
            <hr>
            <span><b>Code Examle</b></span>
            <p> <b>Python code</b>
            <pre>
    depth_list = [1,2,[3,4,[5,6],8,[2,[3,7,8],5,8],[7,8],9]]
    def sum_list_numb(l:list) -> "taking list return sum(number)":
        if len(l) == 1:
            if isinstance(l[0],list):
                riturn = sum_list_numb(l[0])
            else:
                riturn = l[0]
        elif isinstance(l[0],list):
            remove = l.pop(1)
            l[0].append(remove)
            riturn = sum_list_numb(l)
        elif isinstance(l[1], list):
            remove = l.pop(0)
            l[0].append(remove)
            riturn = sum_list_numb(l)
        else:
            remove = l.pop(1)
            l[0] += remove
            riturn = sum_list_numb(l)
        return riturn
    print(sum_list_numb(depth_list))
                </pre>
            <p> <b>JavaScript</b>
            <pre>
	function evenOrOdd(number) {
    		if (number % 2 == 0) {
        		return 'Even'
    		}
    		else {
        		return 'Odd'
    		}
	}
	console.log(evenOrOdd(4))
		</pre>

            </p>
            <hr>
            <span><b>Language</b></span>
            <p><b>Russian </b>(native)</p>
            <p><b>English </b>(B1)</p>
            <p><b>Italian </b>(B1)</p>

        </div>
    </main>
    <footer> Updated 11/03/2023 </footer>


</body>

</html>