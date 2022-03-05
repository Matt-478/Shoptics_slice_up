let i = 0;
let images = [];
let time = 6000;

images[0] = 'https://images.unsplash.com/photo-1540340061722-9293d5163008?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1651&q=80';
images[1] = 'https://images.freeimages.com/images/large-previews/294/logistics-stock-room-1538381.jpg';
images[2] = 'https://images.unsplash.com/photo-1426927308491-6380b6a9936f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1651&q=80';
images[3] = 'https://images.unsplash.com/photo-1536584754829-12214d404f32?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1950&q=80';

function changeImg(){
document.slide.src = images[i];

// Check If Index Is Under Max
if(i < images.length - 1){
// Add 1 to Index
i++; 
} else { 
// Reset Back To O
i = 0;
}

// Run function every x seconds
setTimeout("changeImg()", time);
}

// Run function when page loads
window.onload=changeImg;