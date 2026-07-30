# style.css
.dashboard{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(150px,1fr));
    gap:15px;
    margin:20px 0;
}

.dashboard .card{
    background:#0d6efd;
    color:#fff;
    text-align:center;
    padding:15px;
    border-radius:10px;
    box-shadow:0 2px 6px rgba(0,0,0,.2);
}

.dashboard .card h3{
    margin:0;
    font-size:16px;
}

.dashboard .card p{
    font-size:28px;
    font-weight:bold;
    margin-top:10px;
}

#search,
#statusFilter{
    margin-bottom:15px;
}

footer{
    text-align:center;
    margin-top:30px;
    color:#666;
    font-size:14px;
}
