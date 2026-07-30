/* ===========================
   Waste Pickup Scheduler
   Developed by Elijah Omiwole
   =========================== */

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:Arial, Helvetica, sans-serif;
    background:#f4f7fb;
    color:#333;
    line-height:1.6;
    padding:20px;
}

.container{
    max-width:1000px;
    margin:auto;
    background:#fff;
    padding:25px;
    border-radius:12px;
    box-shadow:0 5px 15px rgba(0,0,0,.1);
}

h1{
    text-align:center;
    color:#0d6efd;
    margin-bottom:10px;
}

h2{
    margin:25px 0 15px;
    color:#222;
}

p{
    margin-bottom:10px;
}

/* Dashboard */

.dashboard{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(180px,1fr));
    gap:15px;
    margin:25px 0;
}

.dashboard .card{
    background:#0d6efd;
    color:#fff;
    padding:20px;
    border-radius:10px;
    text-align:center;
    box-shadow:0 3px 8px rgba(0,0,0,.2);
}

.dashboard .card h3{
    font-size:16px;
    margin-bottom:10px;
}

.dashboard .card p{
    font-size:30px;
    font-weight:bold;
}

/* Form */

form{
    margin-top:20px;
}

input,
textarea,
select{
    width:100%;
    padding:12px;
    margin:10px 0;
    border:1px solid #ccc;
    border-radius:6px;
    font-size:16px;
}

textarea{
    resize:vertical;
    min-height:100px;
}

button{
    width:100%;
    padding:12px;
    background:#198754;
    color:white;
    border:none;
    border-radius:6px;
    font-size:17px;
    cursor:pointer;
    transition:.3s;
}

button:hover{
    background:#157347;
}

/* Search */

#search{
    margin-top:20px;
}

#statusFilter{
    margin-bottom:20px;
}

/* Pickup Cards */

.card{
    background:#fafafa;
    border-left:6px solid #0d6efd;
    border-radius:8px;
    padding:15px;
    margin:15px 0;
    box-shadow:0 2px 5px rgba(0,0,0,.1);
}

.card h3,
.card h4{
    color:#0d6efd;
    margin-bottom:8px;
}

.card p{
    margin:5px 0;
}

/* Status Badges */

.badge{
    display:inline-block;
    padding:6px 12px;
    border-radius:20px;
    color:white;
    font-size:13px;
    font-weight:bold;
}

.pending{
    background:#ffc107;
    color:#222;
}

.completed{
    background:#198754;
}

.today{
    background:#dc3545;
}

/* Action Buttons */

.action-btn{
    padding:8px 12px;
    margin:5px;
    border:none;
    border-radius:5px;
    cursor:pointer;
    color:white;
}

.edit-btn{
    background:#0d6efd;
}

.delete-btn{
    background:#dc3545;
}

.complete-btn{
    background:#198754;
}

/* Feedback */

#feedbackList .card{
    border-left-color:#198754;
}

/* Footer */

footer{
    margin-top:35px;
    text-align:center;
    color:#777;
    font-size:14px;
}

/* Responsive */

@media(max-width:768px){

.dashboard{
grid-template-columns:1fr;
}

.container{
padding:15px;
}

button{
font-size:16px;
}

h1{
font-size:28px;
}

}
