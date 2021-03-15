const fs = require("fs");
async function main() {
  
}
function make_data(o) {
  return {
    player: {},
    possessed: {
      type: o.from,
      nbt: o.fromd
    }
    entity: {
      type: o.to,
      nbt: o.tod
    }
  }
}
function make_Size(s) {
  return JSON.stringify({Size:s});
}
main();