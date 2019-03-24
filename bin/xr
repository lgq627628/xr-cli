#!/usr/bin/env node
const program = require('commander')

// 定义当前版本
// 定义使用方法
// 编写四个指令
program
  .version(require('../package').version)
  .usage('<command> [options]')
  .command('add', 'add a new template')
  .command('delete', 'delete a template')
  .command('list', 'list all the templates')
  .command('init', 'generate a new project from a template')
  
// 解析命令行参数
program.parse(process.argv)