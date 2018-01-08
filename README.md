# hackEverwing

InstanceCache.prototype.writeDirtyInstancesToState = function(e) //Watch video to understand how to use this script

//MAX gems
 
var _r1 = new RegExp("Currency:ge.*");
 
for (var i = 0; i < e.instances.length; i++) {
    if (_r1.test(e.instances[i].modelID)) {
        e.instances[i].value = 99999;
    }
}

var _r1 = new RegExp("Item:sidekick:.*");
 
for (var i = 0; i < e.instances.length; i++) {
    if (_r1.test(e.instances[i].modelID)) {
        e.instances[i].stats.maturity = 3;
        e.instances[i].stats.xp = 125800;
        e.instances[i].stats.zodiac = 2;
        e.instances[i].stats.zodiacBonus = 2;
    }
}
