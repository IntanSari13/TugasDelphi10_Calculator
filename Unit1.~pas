unit Unit1;

interface

uses
  Windows, Messages, SysUtils, Variants, Classes, Graphics, Controls, Forms,
  Dialogs, StdCtrls, ExtCtrls;

type
  TForm1 = class(TForm)
    Panel1: TPanel;
    Panel2: TPanel;
    Edit1: TEdit;
    Label1: TLabel;
    Label2: TLabel;
    Edit2: TEdit;
    Panel3: TPanel;
    Button1: TButton;
    Button2: TButton;
    Button3: TButton;
    Button4: TButton;
    Label3: TLabel;
    Edit3: TEdit;
    Panel4: TPanel;
    Button5: TButton;
    procedure Button5Click(Sender: TObject);
    procedure Button1Click(Sender: TObject);
    procedure Button2Click(Sender: TObject);
    procedure Button3Click(Sender: TObject);
    procedure Button4Click(Sender: TObject);
  private
    { Private declarations }
  public
    { Public declarations }
  end;

var
  Form1: TForm1;
  nilai1,nilai2,hitung:real;

implementation

{$R *.dfm}

procedure TForm1.Button5Click(Sender: TObject);
begin
Edit1.Clear;
Edit2.Clear;
Edit3.Clear;
end;

procedure TForm1.Button1Click(Sender: TObject);
begin
      nilai1:= StrToFloat(Edit1.Text);
      nilai2:= StrToFloat(Edit2.Text);

      hitung:= nilai1+nilai2;

      Edit3.Text:= FloatToStr(hitung);
end;

procedure TForm1.Button2Click(Sender: TObject);
begin
      nilai1:= StrToFloat(Edit1.Text);
      nilai2:= StrToFloat(Edit2.Text);

      hitung:= nilai1-nilai2;

      Edit3.Text:= FloatToStr(hitung);
end;

procedure TForm1.Button3Click(Sender: TObject);
begin
      nilai1:= StrToFloat(Edit1.Text);
      nilai2:= StrToFloat(Edit2.Text);

      hitung:= nilai1*nilai2;

      Edit3.Text:= FloatToStr(hitung);
end;

procedure TForm1.Button4Click(Sender: TObject);
begin
      nilai1:= StrToFloat(Edit1.Text);
      nilai2:= StrToFloat(Edit2.Text);

      hitung:= nilai1/nilai2;

      Edit3.Text:= FloatToStr(hitung);
end;

end.
