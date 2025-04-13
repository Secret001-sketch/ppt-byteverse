<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>my first project</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css"
        integrity="sha512-Evv84Mr4kqVGRNSgIGL/F/aIDqQb7xQ2vcrdIwxfjThSH8CSR7PBEakCr51Ck+w+/U6swU2Im1vVX0SVk9ABhg=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css">
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header id="header">
        <div id="first">
            <div id="ooo">
                <a href="#">
                    <p class="kuchh">Jobs@NITP </p>
                </a>
                <p>|</p>
                <a href="#">
                    <p class="kuchh">Fee Payment</p>
                </a>
                <p>|</p>
                <a href="#">
                    <p class="kuchh">Intranet</p>
                </a>
            </div>
            <div id="logo">
                <a href="#"><i class="fa-brands fa-facebook ico"></i></a>
                <a href="#"><i class="fa-brands fa-twitter ico"></i></a>
                <a href="#"><i class="fa-brands fa-linkedin ico"></i></a>
                <a href="#"><i class="fa-solid fa-location-dot ico"></i></a>
            </div>
        </div>
    </header>
    <div id="second">
        <div id="sec-one">
            <p>राष्ट्रीय प्रौद्योगिकी संस्थान पटना</p>
            <p>NATIONAL INSTITUTE OF TECHNOLOGY PATNA</p>
        </div>
        <div id="sec-two">
            <a href="#"><img src="nitp.webp" height="90" alt="nitp"></a>
        </div>
        <div id="sec-third">
            <div id="sec-third-one">An Institute of National Importance under Ministry of Education</div>
            <div id="sec-third-sec">(Shiksha Mantralaya), Government of India</div>
        </div>
    </div>
    <div id="third">
        <i class="fa-solid fa-house-chimney"></i>
        <select name="Institute">
            <option value="Institute" style="color: black;">Institute</option>
            <option value="Institute" style="color: black;">About</option>
            <option value="Institute" style="color: black;">NIT Status</option>
            <option value="Institute" style="color: black;">Reports</option>
            <option value="Institute" style="color: black;">Magazine</option>
        </select>
        <select name="admin">
            <option value="administration" style="color: black;">Administration</option>
            <option value="administration" style="color: black;">Visitor</option>
            <option value="administration" style="color: black;">NITs Councils </option>
            <option value="administration" style="color: black;">Deans</option>
            <option value="administration" style="color: black;">HODs</option>
            <option value="administration" style="color: black;">Committees</option>
        </select>
        <select name="acad">
            <option value="academics" style="color: black;">Academics</option>
            <option value="academics" style="color: black;">Department</option>
            <option value="academics" style="color: black;">Admission</option>
            <option value="academics" style="color: black;"> programmes</option>
            <option value="academics" style="color: black;">Patents</option>
        </select>
        <select name="facu">
            <option value="academics" style="color: black;">Faculty & staff</option>
            <option value="academics" style="color: black;">Faculty Directory</option>
            <option value="academics" style="color: black;">Officers Directory</option>
            <option value="academics" style="color: black;">Staff Directory</option>
        </select>
        <select name="stu">
            <option value="student" style="color: black;">Students</option>
            <option value="student" style="color: black;">Scholorship</option>
            <option value="student" style="color: black;">E - Cell</option>
            <option value="student" style="color: black;">Tech Fest</option>
            <option value="student" style="color: black;">SC?ST Cell</option>
        </select>
        <select name="faci">
            <option value="facility" style="color: black;">Facilities</option>
            <option value="facility" style="color: black;">Library</option>
            <option value="facility" style="color: black;">Bank</option>
            <option value="facility" style="color: black;">EMU</option>
            <option value="facility" style="color: black;">ESU</option>

        </select>
    </div>
    <div class="container">
        <div class="wrapper swiper">
            <div class="swiper-wrapper">
                <div class="swiper-slide"><img src="pic1.jpg" alt="" class="card-image"></div>
                <div class="swiper-slide"><img src="pic2.png" alt="" class="card-image"></div>
                <div class="swiper-slide"><img src="pic3.png" alt="" class="card-image"></div>
                <div class="swiper-slide"><img src="pic4.png" alt="" class="card-image"></div>
            </div>
            <div class="swiper-button-prev pre"></div>
            <div class="swiper-button-next nex"></div>
        </div>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>
    <script>
        const swiper = new Swiper('.swiper', {
            loop: true,
            navigation: {
                nextEl: '.swiper-button-next',
                prevEl: '.swiper-button-prev',
            },
            autoplay: {
                delay: 3000,
                disableOnInteraction: false,
            },
        });
    </script>
    <div id="fifth">
        <div id="fif-one"><img src="pic4.png" alt="nitp" width="90%"></div>
        <div id="fif-two">
            <div class="box box1"><i class="fa-solid fa-user-graduate i1"></i></div>
            <div class="box box2"><i class="fa-solid fa-graduation-cap i2"></i></div>
            <div class="box box1"><i class="fa-solid fa-school i1"></i></div>
            <div class="box box2"><i class="fa-solid fa-bolt i2"></i></div>
            <div class="box box1"><i class="fa-solid fa-users i1"></i></div>
            <div class="box box2"><i class="fa-solid fa-plane-departure i2"></i></div>
            <div class="box box1"><i class="fa-solid fa-building i1"></i></div>
            <div class="box box2"><i class="fa-solid fa-hand-holding-dollar i2"></i></div>
        </div>
        <div id="fif-three">
            <img src="pic5.png" alt="nitp" width="90%">
        </div>
    </div>
    <section class="links">
        <div class="section sec1">
            <div class="sec-head">
                <h2>Notice</h2>
                <a href="#">View all</a>
            </div>
            <div class="sec-content">
                <div class="s3">
                    <div class="sec-main">
                        <p>Walk-in-Interview for Technical Staff (on contract) at RAC-S ISRO NIT Patna</p>
                        <p class="date">9 Feb 2024</p>
                    </div>
                    <div class="sec-main">
                        <p>MoU signed on Educational and Scientific Cooperation between NIT Patna and University of
                            Florence, Italy</p>
                        <p class="date">5 feb 2025</p>
                    </div>
                    <div class="sec-main">
                        <p>MoU signed on Educational and Scientific Cooperation between NIT Patna and University of
                            Calabria, Italy</p>
                        <p class="date">1 feb 2025</p>
                    </div>
                    <div class="sec-main">
                        <p>Advertisement for the recruitment of one JRF (DST-SERB sponsored project) position to work on
                            the
                            project titled "Development of Driving Cycle and Vehicle Emission Level for Mid-sized Cities
                            under Adverse Traffic and Environment Conditions" in the Civil Engineering Department Last
                            Date
                        </p>
                        <p class="date">15 jan 2025</p>
                    </div>
                    <div class="sec-main">
                        <p>River Health Monitoring" funded by Centre for Ganga River Basin Management and Studies
                            (c-Ganga),
                            IIT Kanpur.</p>
                        <p class="date">1 jan 2025</p>
                    </div>
                </div>
            </div>
        </div>

        <div class="section sec2">
            <div class="sec-head">
                <h2>Event</h2>
                <a href="#">View all</a>
            </div>
            <div class="sec-content">
                <div class="s3">
                    <div class="sec-main">
                        <p>International Conference on "Urban Resilience and Sustainable Architecture (URSA 2025)" to be
                            held at NIT Patna Campus during 15th -16th November 2025</p>
                        <p>10-02-2025 to 16-03-2025</p>
                        <p>Location: NIT Patna</p>
                        <div class="down">
                            <a href="#"><i class="fa-solid fa-file-arrow-down"></i></a>
                            <a href="#">Dowmload</a>
                        </div>
                        <a href="#">Event link</a>
                    </div>
                    <div class="sec-main">
                        <p>Heat Stress - Climate Adaptation in Different Spatial and Temporal Scale</p>
                        <p>28-7-2025 - 1-8-2025</p>
                        <p>Location: NIT Patna</p>
                        <a href="#">Event link</a>
                    </div>
                    <div class="sec-main">
                        <p>1st International conference on Recent Innovations and Trends in Electrical & Electronics
                            Engineering and Computing (Hybrid Mode)</p>
                        <p>22-5-2025 - 23-5-2025</p>
                        <p>Location: EED, NIT Patna</p>
                        <a href="#">Event link</a>
                    </div>
                    <div class="sec-main">
                        <p>One Week Short Term Course (STC) on Application of Remote Sensing and GIS in Spatial Planning
                        </p>
                        <p>17-5-2025 - 21-5-2025</p>
                        <p>Location: Online Mode</p>
                        <a href="#">Event link</a>
                    </div>
                    <div class="sec-main">
                        <p>International Conference on Innovations and Sustainability in Civil Engineering: Shaping
                            Tomorrow’s Infrastructure</p>
                        <p>14-5-2025 - 16-5-2025</p>
                        <p>Location: NIT Patna (Physical Mode)</p>
                    </div>
                </div>
            </div>
        </div>

        <div class="section sec3">
            <div class="sec-head">
                <h2>Academic Notice</h2>
                <a href="#">View all</a>
            </div>
            <div class="sec-content">
                <div class="s3">
                    <div class="sec-main">
                        <p>Open Ph.D. Viva-voce exam of Ph.D. Research Scholar Aditya Kaushal Ranjan ( Roll No. 185CS27)
                        </p>
                        <p class="date">9 Feb 2024</p>
                    </div>
                    <div class="sec-main">
                        <p>Open Ph.D. Viva-voce exam of Ph.D. Research Scholar Pooja Mishra ( Roll No. 215AR008)</p>
                        <p class="date">9 Feb 2024</p>
                    </div>
                    <div class="sec-main">
                        <p>Announcement For Issue Of Books From General Book Bank For Academic Session 2024-25</p>
                        <p class="date">9 Feb 2024</p>
                    </div>
                    <div class="sec-main">
                        <p>Open Ph.D. Viva-voce exam of Ph.D. Research Scholar Rama Shankar Sahu ( Roll No. 205HS012)
                        </p>
                        <p class="date">9 Feb 2024</p>
                    </div>
                    <div class="sec-main">
                        <p>Venue, Timing & SoP for distribution of Uttariya and Jacket on 27.12.2024 for 13th
                            Convocation
                            2024 to be held on 28.12.2024</p>
                        <p class="date">9 Feb 2024</p>
                    </div>
                    <div class="sec-main">
                        <p>Seat Plan End Semester Exam 13/12/2024 (FN) Patna Campus</p>
                        <p class="date">9 Feb 2024</p>
                    </div>
                    <div class="sec-main">
                        <p>Registration Notice for Semester January-June, 2025 (PG & PhD)</p>
                        <p class="date">9 Feb 2024</p>
                    </div>
                </div>
            </div>
        </div>

    </section>

    <section>
        <div class="director">
            <div class="dir1">
                <p class="x1">ABOUT US</p>
                <p class="x3">National Institute of Technology Patna is the 18th National Institute of Technology
                    created by the Ministry of H.R.D. Government of India after rechristening the erstwhile Bihar
                    College of Engineering Patna on 28. 01. 2004.Read More</p>
                <p class="x2">Vision</p>
                <p class="x3">To contribute to India and the World through excellence in scientific and technical
                    education and research; to serve as a valuable resource for industry and society; and to remain a
                    source of pride for all Indians.</p>
                <p class="x2">Mission</p>
                <p class="x3">To generate new knowledge by engaging in cutting-edge research and to promote academic
                    growth by offering state-of-the-art undergraduate, postgraduate and doctoral programmes To identify,
                    based on an informed perception of Indian, regional and global needs, areas of specialization. Read
                    More</p>
            </div>
            <div class="dir2">
                <img src="pkj.jpg" alt="" style="padding-top: .8rem; width: 90%; height: 60%; background-size: cover;">
                <div class="pk">
                    <p class="p1">Pradip K. Jain</p>
                    <p class="p2">Director, NIT PATNA</p>
                    <p class="p2">director@nitp.ac.in</p>
                    <div class="but-pk">
                        <button class="pke">Email</button>
                        <button class="visit">Visit Profile</button>
                    </div>

                </div>
            </div>
            <div class="dir3">
                <p class="x1">KNOW US</p>
                <P class="x2">About</P>
                <p>Prof. Pradip K. Jain joined as a Lecturer of Electronics Engineering at Institute of Technology,
                    Banaras Hindu University in 1981, and became Professor in the Year 2001. He has made significant
                    contribution in the areas of analysis, modeling and development of high power microwave tubes and
                    gyrotron devices. Currently, he is Director of National Institute of Technology, Patna. Read More
                </p>
                <p class="x2">Director's Message</p>
                <p>It is my pleasure to introduce one of the oldest Technological Institutes of North India, National
                    Institute of Technology Patna, whose history goes back to 1876 when four survey schools were
                    established in Dacca, Hoogly, Cuttack and Patna. The schools at Hoogly and Cuttack failed but those
                    at Dacca and Patna continued to prosper. In 1882, a separate altogether, named as Bihar Industrial
                    School, was opened in the premises of the survey school in Patna college campus.</p>

            </div>
        </div>
    </section>
    <footer>
        <div class="footer">
            <div class="foot1">
                <img src="logo.webp" alt="">
                <p>National Institute of Technology Patna</p>
                <p>Ashok Rajpath, Mahendru, Patna, Bihar 800005</p>
                <div style="display: flex;">
                    <i class="fa-solid fa-phone"></i>
                    <p>0612-2371715</p>
                </div>
                <div style="display: flex;">
                    <i class="fa-solid fa-envelope"></i>
                    <p>info@nitp.ac.in</p>
                </div>
                <div style="display: flex;">
                    <i class="fa-solid fa-globe"></i>
                    <p>www.nitp.ac.in</p>
                </div>
                <div class="sox" style="display: flex; gap: 1.3rem;">
                    <a href="#"><i class="fa-brands fa-facebook"></i></a>
                    <a href="#"><i class="fa-brands fa-twitter"></i></a>
                    <a href="#"><i class="fa-brands fa-linkedin"></i></a>
                    <a href="#"><i class="fa-solid fa-location-dot"></i></a>
                </div>
            </div>

            <div class="foot2 foot">
                <p style="font-size: 1.5rem; font-weight: 600;">Quick Links</p>
                <p>Departments</p>
                <p>NIRF</p>
                <p>New Campus</p>
                <p>RTI</p>
                <p>Magazine(Vol.4)</p>
            </div>
            <div class="foot3 foot">
                <p style="font-size: 1.7rem; font-weight: 600;">Explore</p>
                <p>Campus</p>
                <p> BOG/FC/BWC Minutes</p>
                <p>Convocation 2023</p>
                <p> Senate Minutes</p>
                <p>SC/ST Grievance Cell</p>
                <p>Climate Action Plan</p>
            </div>
            <div class="foot4 foot">
                <p style="font-size: 1.7rem; font-weight: 600;">Useful Links</p>
                <p>How to Reach</p>
                <p>Annual Reports</p>
                <p>National Service Scheme</p>
                <p>Tenders</p>
                <p>Academic Calendar</p>
                <p>Terms of Use</p>
            </div>
            <div class="foot5">

                <div style="display: flex; align-items: center;">
                    <a href="#"><i class="fa-solid fa-location-dot"></i></a>
                    <p style="font-size: 1.7rem; font-weight: 600;">Patna</p>
                </div>
                <div id="live-date-time">
                </div>
                <div id="weather-info">
                    <p>Weather Information:</p>
                    <p id="temperature">Temperature: Loading...</p>
                    <p id="condition">Condition: Loading...</p>
                </div>
            </div>
        </div>
    </footer>
    <script src="script.js"></script>
</body>

</html>
