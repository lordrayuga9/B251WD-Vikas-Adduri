# B251WD-Vikas-Adduri
Task-1:
let resume ={PersonalInfo:{Name:"Vikas Adduri",Contact:"7396208777",Email:"vikky_3000@hotmail.com"},
            AcademicProfile:{TenthClass:{School:"Narayana",percentage:"90.5",Period:"2010-2011"},TwelfthClass:{College:"Narayana",percentage:"94.1",Period:"2011-2013"},BTECH:{University:"SRM University",CGPA:"7.433",Period:"2013-2017"}},
    Skillset:["HTML","JavaScript"],
    PersonalTraits:["Calm and Meticulous","Patient and Quick Learner"],
    Hobbies:["Badminton","E-sports","Anime"]
}
console.log(resume);

Task-2:
how to compare two JSON have the same properties without order?
        var obj1 = { name: "Person 1", age:5 };
        var obj2 = { age:5, name: "Person 1"}

if(Object.keys(obj1).length==Object.keys(obj2).length){
    let b = Object.keys(obj1).length;
    for(let i in obj1){
        if(obj1[i]==obj2[i]){
            b--;
            continue;
        }
        else{
            console.log("They are not equal")
        }
    }
    if(b===0){
    console.log("They are equal")
}

}
else{
    console.log("They are not equal")
}


