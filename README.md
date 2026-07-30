/* ==========================
   Waste Pickup Scheduler
   ========================== */

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial,Helvetica,sans-serif;
}

body{
    background:#f4f6f9;
    color:#333;
    line-height:1.6;
}

.container{
    max-width:900px;
    margin:30px auto;
    background:#fff;
    padding:25px;
    border-radius:10px;
    box-shadow:0 4px 10px rgba(0,0,0,.1);
}

h1{
    text-align:center;
    color:#0d6efd;
    margin-bottom:10px;
}

.subtitle{
    text-align:center;
    color:#666;
    margin-bottom:25px;
}

h2{
    margin:20px 0 15px;
    color:#0d6efd;
}

label{
    display:block;
    margin-top:12px;
    margin-bottom:5px;
    font-weight:bold;
}

input,
textarea,
select{
    width:100%;
    padding:10px;
    border:1px solid #ccc;
    border-radius:6px;
    margin-bottom:12px;
    font-size:15px;
}

textarea{
    resize:vertical;
    min-height:80px;
}

button{
    background:#0d6efd;
    color:#fff;
    border:none;
    padding:12px 18px;
    border-radius:6px;
    cursor:pointer;
    font-size:15px;
    transition:.3s;
}

button:hover{
    background:#084298;
}

.dashboard{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(170px,1fr));
    gap:15px;
    margin:25px 0;
}

.dashboard .card{
    background:#0d6efd;
    color:#fff;
    text-align:center;
    padding:20px;
    border-radius:10px;
    box-shadow:0 2px 8px rgba(0,0,0,.15);
}

.dashboard .card h3{
    font-size:16px;
    margin-bottom:10px;
}

.dashboard .card p{
    font-size:30px;
    font-weight:bold;
}

#pickupList .card,
#feedbackList .card{
    background:#fff;
    border-left:5px solid #0d6efd;
    padding:15px;
    margin-bottom:15px;
    border-radius:8px;
    box-shadow:0 2px 5px rgba(0,0,0,.1);
}

#pickupList .card h3,
#feedbackList .card h3{
    color:#0d6efd;
    margin-bottom:8px;
}

#pickupList button{
    margin-right:10px;
    margin-top:10px;
}

#search,
#statusFilter{
    margin-bottom:15px;
}

footer{
    text-align:center;
    margin-top:35px;
    padding-top:20px;
    border-top:1px solid #ddd;
    color:#666;
    font-size:14px;
}

@media(max-width:768px){

    .container{
        margin:15px;
        padding:20px;
    }

    h1{
        font-size:28px;
    }

    button{
        width:100%;
        margin-top:10px;
    }

    #pickupList button{
        width:100%;
        margin-right:0;
    }

}
