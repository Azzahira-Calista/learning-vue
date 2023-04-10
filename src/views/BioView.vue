<template>
    <div class="bio">
        <h1>Profil Saya</h1>
        <div class="boxes">
            <div class="box-name">
            <h2>Nama Lengkap</h2>
            <p>Calista Azzahira Rusdy</p>
        </div>
        <div class="box-ttl">
            <h2>Tanggal Lahir</h2>
            <p>07-07-2007</p>
        </div>
        </div>
        <div class="p">
                    <p><b>Nama, Bio data singkat</b> Lorem ipsum dolor sit, amet consectetur adipisicing elit. Amet dolores doloribus vel? Placeat porro similique tenetur illo. Quasi neque eum voluptate ab a repellendus soluta fuga tempora blanditiis molestiae? Assumenda.</p>
            <p><b>Motivasi masuk rus dan rpl</b> Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis, ut earum. Nemo placeat iste esse neque ullam inventore illo, nam similique quod adipisci cupiditate autem eaque distinctio atque, nostrum iure?</p>
        </div>
    </div>
</template>

<style>
.p {
    margin-top: 50px;
    text-align: justify;
}
.box-ttl {
    text-align: left;
    box-shadow: rgba(0, 0, 0, 0.15) 2px 2px 5px;
    padding: 20px;

}
.box-name {
    text-align: left;
    box-shadow: rgba(0, 0, 0, 0.15) 2px 2px 5px;
    padding: 20px;
   
}
.boxes {
    display: flex;
    flex-direction: row;
    justify-content: space-around;
}
h1 {
    text-align: left;
}
.bio {
    margin: auto;
    width: 60%;
}
</style>