<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Colpedia Admin Panel</title>
    <style>

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {

            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
        }

        .slideshow {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
        }

        .slideshow img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            position: absolute;
            opacity: 0;
            transition: opacity 1s ease-in-out;
        }

        .slideshow img.active {
            opacity: 1;
        }
        
        nav div {
            background-color: rgba(173, 62, 34, 0.769);
            color: aliceblue;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 5%;
            font-size: 1.4em;
        }
        
        nav div h2 {
            text-shadow: 0 0 10px wheat;
        }
        
        nav div h5 {
            display: flex;
            background-color: rgb(10, 14, 49);
            align-items: center;
            padding: 10px;
            border-radius: 5px;
            text-decoration: none;
            color: whitesmoke;
            transition: background-color 0.3s, box-shadow 0.3s;
        }
        
        nav div h5:hover {
            background-color: rgb(157, 14, 14);
            box-shadow: -1px -1px 4px black;
        }
        
        .main {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        
        .main h1 {
            width: fit-content;
            text-align: center;
            padding: 15px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            margin:0 5%;
            background-image: url(https://worldofprintables.com/wp-content/uploads/2023/06/Summer-Sky-Wallpaper.jpg);
            background-size: cover;
             background-position: center;
             -webkit-background-clip: text;
             background-clip: text;
             color: transparent;
        }

        body::-webkit-scrollbar{
             background-color: transparent;
        }

        body::-webkit-scrollbar-thumb{
            background: linear-gradient(orange ,white ,green);
            border-radius: 20px;
        }
        
        form {
            border: 2px solid;
            border-radius: 5px;
            width: 100%;
            max-width: 700px;
            color: white;
            padding: 20px;
            background-image: url(data:image/jpeg;base64,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);
            background-size: cover;
            background-position: center;
            margin-bottom: 3%;
        }
        
        form div {
            display: flex;
            flex-direction: column;
            margin-bottom: 10px;
        }
        
        input {
            padding: 10px;
            font-size: 1em;
            width: 100%;
            border: 1px solid #ccc;
            border-radius: 5px;
            box-sizing: border-box;
        }
        
        input[type=file] {
            background-color: rgb(200, 200, 255);
            cursor: pointer;
        }
        
        input[type=submit] {
            width: 100%;
            margin: 10px auto;
            background-color: rgb(32, 32, 210);
            border-radius: 4px;
            color: white;
            font-weight: 700;
            cursor: pointer;
        }
        
/* Style for the "Add Department" button */
.add-department-btn {
    padding: 10px;
    margin: 10px 0;
    background-color: purple;
    border: none;
    border-radius: 5px;
    color: rgb(6, 15, 87);
    font-size: 1.2em;
    cursor: pointer;
    transition: background-color 0.3s, color 0.3s;
}

.add-department-btn:hover {
    background-color: rgb(0, 162, 101);
    color: white;
}

        .colleges {
            display: flex;
            justify-content: space-between; /* Adjust as needed */
            align-items: center;
            box-shadow: 3px 3px 0;
            font-size: 1.1em;
            font-family: Arial, Helvetica, sans-serif;
            padding: 0 2vw;
            color: rgb(235, 231, 226);
            font-weight: 600;
            flex-wrap: wrap; /* Allow content to wrap to the next line */
        }
                    
        .colleges div {
            margin: 3px; /* Reduced margin for spacing */
            padding: 6px; /* Reduced padding for spacing */
            border-radius: 5px;
        }
     
        .dlt-btn {
            background-color: rgb(216, 18, 18);
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            cursor: pointer;
            color: #111;
        }
        
        .dlt-btn:hover {
            background-color: rgb(255, 50, 50);
            color: white;
        }
        
/* Footer styles */
footer {
    background-color: #333;
    color: #fff;
    padding: 20px 0 0 0;
}

.footer-content {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
}

.footer-section {
    flex: 1;
    padding: 0 20px;
}

.footer-section h2 {
    color: #00bcd4;
}

.footer-section p {
    line-height: 1.6;
}

.footer-section ul {
    list-style: none;
    padding: 0;
}

.footer-section a {
    color: #fff;
    text-decoration: none;
    transition: color 0.3s;
}

.footer-section a:hover {
    color: #00bcd4;
}

.footer-bottom {
    text-align: center;
    padding: 10px 0;
    background-color: #111;
}

.footer-bottom p {
    font-size: 0.8em;
}


        @media screen and (max-width: 768px) {
            nav div {
                flex-direction: column;
                text-align: center;
            }
        
            nav div h5 {
                margin-top: 10px;
            }
        
            .main {
                margin: 5vh 5%;
            }
        }
        

    </style>
  </head>
  <body>
    <nav>
      <div>
        <h2><u>Welcome To Colpedia Admin Panel</u></h2>
        <a href="/" style="text-decoration: none; color:whitesmoke"><h5>Log Out</h5></a>
      </div>
    </nav>
    <div class="slideshow">
        <img src="f2723b92b22439c811371c2f91eb1980.jpg" class="active" alt="Image 1">
        <img src="c060269d2efd8ae229f76f83f58d69fb.jpg" alt="Image 2">
        <img src="9368ebfc06e65b611b242f92690f8092.jpg" alt="Image 3">
        <img src="43a8fdb1b821ee4e1c08da8c81691b37.jpg" alt="Image 3">

        <!-- Add more images as needed -->
    </div>
    <div class="main">
        <h1>ADD A NEW COLLEGE ON SITE</h1>

        <form id="collegeForm" action="/addCollege" method="post" enctype="multipart/form-data">
            <div>
                <label for="college_name">College Name :</label>
                <input placeholder="Enter College Name" type="text" required  name="college_name">
            </div>
            
            <div>
                <label for="university_name">University Name :</label>
                <input placeholder="Enter University Name" type="text" required  name="university_name">
            </div>
            
            <div>
                <label for="college_type">College Type :</label>
                <input placeholder="Enter College Type" type="text" required  name="college_type">
            </div>

            <div>
                <label for="district_name">District Name :</label>
                <input placeholder="Enter District Name" type="text" required  name="district_name">
            </div>

            <div>
                <label for="state_name">State Name :</label>
                <input placeholder="Enter State Name" type="text" required  name="state_name">
            </div>

            <div>
                <label for="admission_fees">Addmission Fees :</label>
                <input placeholder="Enter The Amount" type="text" required  name="admission_fees">
            </div>

            <div>
                <label for="semester_fees">Semester Fees :</label>
                <input placeholder="Enter The Amount" type="text" required  name="semester_fees">
            </div>

           <div id="depertment">
                <label for="department">Department :</label>
                <input placeholder="Enter Department" type="text" name="department" class="department" oninput="this.value = this.value.toUpperCase()">
           </div>
           <div style="justify-content:center; " >
            <div class="add-department-btn" onclick="addDepertment()">ADD DEPERTMENT  </div>
        </div>


            <div>
                <label for="photo">College Photo :</label>
                <input type="file" required  name="photo">
            </div>
            
            <div>
                <input type="submit"  value="Submit">
            </div>
        </form>
    </div>
<!-- <div>View And Update All Colleges</div> -->
<div id="AllColleges">
<h1 style="background-color: rgb(188, 11, 11); text-align:center">View And Delete A College</h1>
</div>

<script>
     const slides = document.querySelectorAll('.slideshow img');
        let currentSlide = 0;

        function nextSlide() {
            slides[currentSlide].classList.remove('active');
            currentSlide = (currentSlide + 1) % slides.length;
            slides[currentSlide].classList.add('active');
        }

        setInterval(nextSlide, 3000); // Change image every 3 seconds
    // This function prevents back navigation to authenticated pages
    function preventBack() {
      window.history.forward();
    }
    // Call the preventBack function when the page is loaded
  </script>

  <script>
    const form = document.getElementById('collegeForm');

    form.addEventListener('submit', async (event) => {
      event.preventDefault();
      // Create a FormData object to serialize the form data
      const formData = new FormData(form);
      // Send a POST request to the server
      try {
        const response = await fetch('/addCollege', {
          method: 'POST',
          body: formData,
        });
  
        if (response.ok) {
          // Handle a successful response (e.g., display a success message)
          alert('College added successfully.');
          location.reload();
        } else {
          // Handle errors (e.g., display an error message)
          alert('Failed to add a new college.');
        }
      } catch (error) {
        // Handle network errors (e.g., connection issues)
        alert('Network error:', error);
      }
    });
    function insertAfter(referenceNode, newNode) {
        referenceNode.parentNode.insertBefore(newNode, referenceNode.nextSibling);
      }
    function addDepertment(){
        let dep = document.getElementById('depertment');
        let newNode = document.createElement('div');
        newNode.innerHTML = dep.innerHTML;
        insertAfter(dep,newNode)
    }
  </script>
  <!-- get colleges and delete -->
  <script>
//get college API
let allCollege = fetch('https://collegeserver.onrender.com/collegesAdminPanel');
allCollege.then(response=>{
    if(!response.ok){
        throw new Error(`HTTP error ! Status: ${response.status}`);
    }
    return response.json();
})
.then(data=>{
    //console.log(data);
    let AllColleges = document.getElementById('AllColleges');
    data.forEach(college=>{
        //console.log(college.college_name)
        let div = document.createElement('div');
        let id = college._id;
        div.innerHTML = `
        <div class="colleges">
            <div><div id="name">${college.college_name}</div> </div>
        <div><div class="district">${college.district_name}</div> </div>
        <div class="dlt-btn"><div onclick="deleteCollege('${id}')">DELETE</div>
    </div>
        </div>
        `;
        AllColleges.appendChild(div);
    })
})
async function deleteCollege(id) {
    const url = `https://collegeserver.onrender.com/deleteCollege/${id}`;
let confirm = prompt("Type 'D' For Confirmation");
if (confirm == 'D' || confirm == 'd'){
    try {
        const response = await fetch(url, {
            method: 'POST', // or 'DELETE'
        });

        if (!response.ok) {
            throw new Error(`HTTP error! Status: ${response.status}`);
        } else {
            console.log(`College with ID ${id} deleted successfully.`);
            window.location.reload();
        }
    } catch (error) {
        console.log(`There was an error: ${error}`);
    }
}else{
    alert("Item Not Deleted")
}
}

  </script>

  <footer>
    <div class="footer-content">
        <div class="footer-section about">
            <h2>About Us</h2>
            <p>Explore a vast database of colleges spanning diverse disciplines, from engineering and medicine to arts and social sciences. Each college profile offers key information such as courses offered, admission criteria, campus facilities, faculty credentials, and more.
            </p>
        </div>

        <div class="footer-section contact">
            <h2>Contact Information</h2>
            <p>Email: bwebsite865@gmail.com</p>
            <p>Phone: +91 7501728816</p>
        </div>

        <div class="footer-section links">
            <h2>Quick Links</h2>
            <ul>
                <li><a href="/">Home</a></li>
                <li><a href="/about">About</a></li>
                <li><a href="/contact">Contact</a></li>
            </ul>
        </div>
    </div>

    <div class="footer-bottom">
        <p>&copy; 2023 Class Buddy JR. All rights reserved.</p>
    </div>
</footer>
  </body>
</html>
