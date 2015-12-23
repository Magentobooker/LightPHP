# LightPHP
LightPHP is light PHP framework, MVC structure, scalable, reliable and modulized.

Controller loads language file, model, template... and prepare all data used in tmeplate file.

For Example
$this->load->language('common/home');

$this->load->model('account/customer');

$this->load->view('default/template/common/header.phtml', $data);
